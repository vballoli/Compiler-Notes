# Structure of a Compiler

As previously mentioned, compiler has 5 parts to it: 

1. Lexical Analysis

2. Parsing

3. Semantic Analysis

4. Optimization

5. Code Generation

* Lexical analysis aims to divide the program into __tokens__ analogous to text -> words in plain English. 
For example in if x == y then z=1; else z=2;
- *if*, *else* and *then* are keywords
- *x*, *y*, *z* are variables
- *1* and *2* are constants
- *==*, *=* are operators
- ** Here, spaces serve as tokens that act as separators for the above mentioned items.

* Parsing - diagramming sentences i.e identifies the role of each words in the sentence.

* Semantic analysis is performed to catch inconsistencies and errors. Programming languages have very strict rules to avoid ambiguities.

* Optimization can modify the program to run faster or reduce memory footprint or reduce power usage or network usage.

* Code generation produces code in another programming language analogous to translating one language to another.

The overall structures of almost all compilers adhere to the above outline.

Modern compilers have very less lexical analysis and parsing, fair amount of semantic analysis, large amount of optimization and litte code generation.


