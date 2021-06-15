Use expanded syntax: For JavaScript we use expanded syntax, with each line of JS on a new line, the opening brace of a block on the same line as its associated statement, and the closing brace on a new line. This maximizes readability, and again, promotes consistency on MDN.
JavaScript comments: Use JS-style comments to comment code that isn't self-documenting
Variable naming: For variable names use lowerCamelCasing, and use concise, human-readable, semantic names where appropriate.
Declaring variables: When declaring variables and constants, use the let and const keywords, not var. If a variable will not be reassigned, prefer const
Ternary operators: Ternary operators should be put on a single line
Use strict equality: Always use strict equality and inequality
Use shortcuts for boolean tests: Use shortcuts for boolean tests — use x and !x, not x === true and x === false
Strings: Use template literals
Use textContent, not innerHTML
General purpose looping: When using for/for...of loops, make sure to define the initializer properly, with a let keyword:
