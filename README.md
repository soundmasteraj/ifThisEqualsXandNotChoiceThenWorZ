# ifThisEqualsXandNotChoiceThenWorZ
Complex logic, in minimalist expression.  Supplying a variable y, with w and z yields the following states: ONE purely of each source, ONE of NO source, and ONE of combined source (of each y, w, and z) when choice is true, then at least once; choice is negated; while each source may be true or untrue; all while x, a constant; remains unchanged.


void lifeBegin() {
  infinity = infinity == x == !choice ?  w  : z;
doSomethingBasedOn(infinity, !choice);
someTimePasses(anyAmount);
 choice = !choice;
doSomethingBasedOn(infinity, choice);
someTimePasses(anyAmount);
 infinity =  w;
doSomethingBasedOn(infinity, !choice);
someTimePasses(anyAmount);
infinity =  y;
doSomethingBasedOn(infinity, choice);
}
