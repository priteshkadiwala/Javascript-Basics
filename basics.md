# JavaScript Basics
The language is very similar to Java but has a few changes. 

## 1. Data Types and Variables
Example:

```javascript
var num = 1;
var string = "hi";
var array = {1, "hi"};
```

To initialize a data type, only "var" is needed as JavaScript would automatically allot the data type to the variable. 

Thats awesome!!!!!

## 2. Conditionals
Ternary conditional example:

```javascript
var isGoing = true;
var color = isGoing? "Green" : "Red";
```

Again the to initialize the variable one could put in the conditional in the expression.

## 3. Functions
Functions are pretty cool in JS. 
Simple function example:

```javascript
function add(x, y) {
  // function body
  var sum = x + y;
  return sum; // return statement
}

// 1 and 2 are passed into the function as arguments
var sum = add(1, 2);
```

### 1. Shadowing
Shadowing is a cool concept in JS.

So for example, the code:

```javascript
var x = 1;

function addTwo() {
  x = x + 2;
}

addTwo();
x = x + 1;
console.log(x);
```

The global "x" value will change and x = 4

However,

```javascript
var x = 1;

function addTwo() {
  var x = x + 2;
}

addTwo();
x = x + 1;
console.log(x);
```
 
The global "x" value will not change and x = 2
The difference comes by adding the "var"

## 4. Arrays
Arrays in JS have pretty cool functions such as "push", "pop", "Length", "splice", "reverse", "shift" and many more.

Documentation of the methods: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array#Mutator_methods

Finally, this is the core basics of JS. Great help!







