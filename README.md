# Lesson1-week1
-IMPORT :
+ import <#module#>
+ import <#import kind#><module#>,<#symbol name#>

-COMMENTS:
+ // comment single-line
+ /* ... */ multiline comment

-DECLARATIONS:
-Gammar of a declaration:import, constant, variable, typealias, function, enum, struct, class , actor, protocol, initialier, denitilizer
-Grammar of a top level declaration
 let <#constant name#>: <#type#> = <#expression#>
-Function Declaration
 + func <#function name#>(<#parameters#>) ->#return type#> {
  <#statements#> }
  + func <#function name#>(#parameters#>) {
   <#statements#> }
-Parameters Names: <#parameter name#> : <#parameter type#>
-Parameters Modifiers: INOUT, BORROWING, CONSUMING
+ In-Out Parameters: must be prefixed with an ampersand (&) to mark the function call can change the argument's value
+ Borrowing and Consuming Parameters***********
-Special Kinds of Parameters: "_ : <#parameter type#> " can be ignored
-METHODS WITH SPECIAL NAMES: dynamicCallable******

*************KEYWORDS******************
-Used in declarations: associatedtype, class, deninit, enum, extension , func, import, init, inout, internal, let, open, operator, private , public, precendencegroup, protocol, rethrows, static, struct, subscript, typealias and var
-Used in statements: break, case, match, continue, default, do, else, for, if, in, repeat, return,where, while.
-Used in expressions and types: as, any, await, catch, false, is, nil, rethrows, selft, super, throws, true, try
-Used in patterns: _.
-That begin number sign(#): #availabel, #colorLiteral, #else, #elseif, #endif, #fileLiteral, #if, #imageLiteral, #keyPath, #selector, #sourceLocation, #unavailable
-Reserved in particular contexts: associativity, convenience, did set, dynamic, final, get,, indirect, protocol


