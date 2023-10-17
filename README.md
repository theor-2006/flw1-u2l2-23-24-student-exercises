# Lesson 2.2: Arrow Functions & Review

## Table of Contents
1. [Arrow Functions](#arrow-functions)
2. [Single Parameter](#single-parameter)
3. [Multiple Parameters](#multiple-parameters)

## Arrow Functions

### What is a function?

In programming, a function is a reusable block of code that performs a specific task. Functions help organize your code, make it more readable, and reduce redundancy.

### Why do we use functions in programming?

- **Modularity**: Functions allow you to break down complex problems into smaller, manageable tasks.
- **Reusability**: You can use the same function in multiple parts of your code.
- **Readability**: Functions make your code more organized and easier to understand.

### Quick Recap

Arrow functions provide a concise syntax to write functions in JavaScript. They are declared with the following structure:

```javascript
const functionName = () => {
  // Your code here
}
```

Here's an example:

```javascript
const greet = () => {
  console.log('Hello!');
}
```

You can often convert a regular function into an arrow function. For example:

```javascript
// Regular function
function greet() {
  console.log('Hello!');
}

// Arrow function
const greet = () => {
  console.log('Hello!');
}
```

### Code Along

Use the `arrow.js` file to complete the tasks. As you code, make sure you are following along with the examples provided in the lesson.

## Single Parameter

In this section, you'll learn about functions that take a single parameter.

### Function Declaration with Parameters

To declare a function with a parameter, use the following syntax:

```javascript
function functionName(parameterName) {
  // Your code here
}
```

Here's an example:

```javascript
function squareNum(num) {
  return num * num;
}
```

### Function Call with Arguments

When calling a function with parameters, you provide arguments. Arguments are the actual values that you want to use inside the function. For example:

```javascript
squareNum(7); // Calling squareNum with the argument 7
squareNum(6); // Calling squareNum with the argument 6

let userInput = input.value; // Assuming input.value holds a number
squareNum(userInput); // Calling squareNum with a variable as the argument
```

## Multiple Parameters

Functions can also take multiple parameters.

```javascript
function greet(name1, name2) {
  console.log(`Hi ${name1} & ${name2}!`);
}
```

### Multiple Parameters - Order Matters

When using multiple parameters, it's important to place the arguments in the right order when you call the function. The order of the arguments should match the order of the parameters in the function declaration.

```javascript
greet("Lucy", "Pablo"); // Correct order
```


Happy coding 😊