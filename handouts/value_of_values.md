### Value of Values

What's the value and data type of `0`? ____________________________________________________________________

What's the "return" value of `23`? ___________________________________________________________________

What's the "return" value of `"A"` ________________________________________________________________

What's the data type returned from `3 < 2` or `"2" == 2"` ___________________________________________________________________

What's the data type returned from `isNaN(3.141)` ___________________________________________________________________

What's the difference between `==` and `===` _____________________________________________________________________________________________________________________________________________________________________

What's the data type returned by `confirm("Do you want to continue?")` __________________________________________________________________

What's the data type returnd by `prompt("What is your favorite number?")`  __________________________________________________________

What's the data type returned by `parseFloat("banana")` and `parseFloat(3.14159)` ______________________

```js
function one() {
    console.log(2)
    return 1;
    return 3;
}
```

What's return value of calling  `one()` _________________________________________________________________

What is a side effect of calling `one()`____________________________________________________________________________________

What's a line of code in `one()` that will never run _____________________

What's the value returned by the operation `one() + 4`  ________

What's the value returned by the operation `one() / 2` ________

```js
var n = 5;

function addOneToArgument(n) {
	return n + 1;    
}

function addOneToGlobal() {
    return n + 1;
}
```

Which of these is a more reliable function? `addOneToArgument` or `addOneToGlobal`? Why?

	








```js
function a() { console.log("Hello, World!") }

function b() { return console.log("Hello, World!") }

function c() { return "Hello, World"! }
```

What's the return value of `a()` _________________________________________________________________

What's the return value of `b()` _________________________________________________________________

What's the return value of `c()` _________________________________________________________________



```js
function isNumeric(n) {
    var parsedValue = parseFloat(n);
    var isNumber = !isNaN(parsedValue);
    return isNumber;
}
```



What's the data type returned by `isNumeric("23")` or `isNumeric("mango")` 



