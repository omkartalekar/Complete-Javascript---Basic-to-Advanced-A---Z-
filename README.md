# Complete-Javascript---Basic-to-Advanced-A---Z-

# JavaScript Basics

## Variables & Data Types

### Variable Declarations
- **`var`**: A function-scoped or globally-scoped variable declaration.
- **`let`**: A block-scoped variable declaration. Allows reassignment.
- **`const`**: A block-scoped variable declaration. Cannot be reassigned after initialization.

### Primitive Data Types:
- **`string`**: Represents a sequence of characters.
- **`number`**: Represents numerical values (both integers and floating point).
- **`boolean`**: Represents either `true` or `false`.
- **`null`**: Represents the intentional absence of any value.  
  **Type**: `object` (This is a historical quirk in JavaScript).  
  **Usage**: Used when you want to intentionally assign an empty value to a variable or object.  
- **`undefined`**: Indicates that a variable has been declared but not assigned a value, or a function doesn’t return anything.  
  **Type**: `undefined`.  
  **Usage**: Default value for uninitialized variables or when arguments are missing in functions.
- **`symbol`**: A unique, immutable primitive value used to create unique object property keys.

### Null vs Undefined:
- **`null`**: Explicitly assigned to a variable to indicate that it is intentionally empty or has no value.
- **`undefined`**: Indicates that a variable has not been assigned a value, or that a function doesn't return anything.

## Reference Data Types:
- **Object**: A collection of key-value pairs.
- **Array**: An ordered list of values.
- **Function**: A block of reusable code that can be executed when invoked.

## Control Structures:
- **`if`**: Used for conditional execution.
- **`else`**: Defines an alternative block of code to execute if the `if` condition is false.
- **`switch`**: A control structure for multiple conditional branches based on different possible values.

## Loops:
- **`for`**: A loop that executes a block of code a set number of times.
- **`while`**: A loop that executes as long as the condition is true.
- **`do-while`**: Similar to `while`, but guarantees that the code will run at least once.
- **`for...of`**: A loop that iterates over iterable objects (e.g., arrays).
- **`for...in`**: A loop that iterates over the keys of an object.

## Functions:
### Function Declarations vs Expressions
- **Function Declarations**: Named functions defined with the `function` keyword.
  ```javascript
  function greet() {
    console.log("Hello!");
  }
  
- **Function Expressions**: Functions defined as part of an expression, often assigned to variables.
 ```javascript
const greet = function() {
  console.log("Hello!");
}
