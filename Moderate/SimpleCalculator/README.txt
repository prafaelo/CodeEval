"Simple Calculator" from CodeEval

Parses via recursive descent. A major hurdle was the output
format - non-integral values must have 5 digits of precision
to the right of the decimal point, but with trailing zeros
suppressed.  This is surprisingly tricky in C++.

Largely based on Stroustrup: "Programming: Principles and Practice Using C++,"
but their calculator implementation had to be extended to support the
exponentiation operator, and to use a line from a file argument as the
basic unit of input (one expression per line).

