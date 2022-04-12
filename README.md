**Table of Contents**
##  [Dynamically Typed vs Statically Typed](https://stackoverflow.com/questions/1517582/what-is-the-difference-between-statically-typed-and-dynamically-typed-languages)
  1. Dynamically Typed  
     + A language is dynamically typed if the type is associated with run-time values, and not named variables/fields/etc. 
     + Dynamically typed programming languages do type checking at run-time as opposed to compile-time.
     +  dynamically typed language variables' types are dynamic, meaning after you set a variable to a type, you CAN change it. That is because typing is associated with the value it assumes rather than the variable itself.
     + Advantage is  that programmer can write a little quicker because you do not have to specify types every time
       + Examples: Perl, Ruby, Python, PHP, JavaScript,
  3. Statically Typed  
      + A language is statically typed if the type of a variable is known at compile time
      + do type checking (i.e. the process of verifying and enforcing the constraints of types) at compile-time as opposed to run-time.
      + statically typed language variables' types are static, meaning once you set a variable to a type, you cannot change it. That is because typing is associated with the variable rather than the value it refers to.
      + The main advantage here is that all kinds of checking can be done by the compiler, and therefore a lot of trivial bugs are caught at a very early stage.
        + Examples: C, C++, Java, Rust, Go, Scala
      
## [Scripting Language vs Programming(compiled) Language](https://stackoverflow.com/questions/17253545/scripting-language-vs-programming-language) 
  1. Scripting languages are programming languages that don't require an explicit compilation step.  
      + C vs javascript (JS Doesn't required explicit compilation step)  
      + During compilation of programming language compiler takes complete source file and converts it into machine code - 
          *  no need to share source code
          *  Fast as already compiled  
      + During interpretation of Scripting language single line of code is converted into machine code 
        - need to share source code
        - slow execution speed as conversion happens on the go
  2. Programming Language : Is compiled to machine code and run on the hardware of the underlying Operating System i.e. it targets computing system.
  3. Scripting Language : Is unstructure subset of programming language. It is generally interpreted and it  targets a software system  
  4. If we say that the real difference is whether it is compiled or not, then we have a problem because when Javascript runs in V8 is compiled and when it runs in Rhino is not.


