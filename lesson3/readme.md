<h1>Lesson 3</h1>


- Number constructor
- Number methods
- Type conversion and coercion
- Truthy and Falsy
- If else
- isNaN
- Boolean constructor
- Logical operators
- Nullish coalescing operator ??
- Conditional (ternary) operator
- Switch case



<br><br>

# Number constructor

## Properties

| Property          | Description                                                                                                                       |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| EPSILON           | The Number.EPSILON static data property represents the difference between 1 and the smallest floating point number greater than 1 |
| MAX_VALUE         | The largest number possible in JavaScript                                                                                         |
| MIN_VALUE         | The smallest number possible in JavaScript                                                                                        |
| MAX_SAFE_INTEGER  | The maximum safe integer (2^53 - 1)                                                                                               |
| MIN_SAFE_INTEGER  | The minimum safe integer -(2^53 - 1)                                                                                              |
| POSITIVE_INFINITY | Infinity (returned on overflow)                                                                                                   |
| NEGATIVE_INFINITY | Negative infinity (returned on overflow)                                                                                          |


<br><br>

## Methods

- Number.isInteger()
- Number.isSafeInteger()
- Number.parseInt(n)
- Number.parseFloat(n)

<hr><br><br><br><br>

# Number methods


- n.toString()
- n.toExponential()
- n.toFixed()
- n.toPrecision()

<hr><br><br><br><br>

# Type conversion and coercion



## … → number

 - Number constructor
 - +n → optimal
 - n * 1

<br>

## … → string

- String constructor
- toString() → optimal
- n + “”


<hr><br><br><br><br>


# Truthy and Falsy

   ## Falsy
- false
- 0
- -0
- 0n
- -0n
- ""
- null
- undefined
- NaN


<br>

## Truthy

- {}
- []
- 42
- "0"
- "false"
- -42
- 12n
- 3.14
- -3.14
- Infinity
- -Infinity
-  ETC...


<hr><br><br><br><br>

# If else


## if else

    if (Truthy/Falsy) {
         console.log("Truthy");
       } else {
         console.log("Falsy");
      }

<br>

## else if


    if (condition1) {
        //  block of code to be executed if condition1 is true
    } else if (condition2) {
        //  block of code to be executed if the condition1 is false and condition2 is true
    } else {
        //  block of code to be executed if the condition1 is false and condition2 is false
    }

<hr><br><br><br><br>

# isNaN

> The isNaN() function determines whether a value is NaN when converted to a number.

<hr><br><br><br><br>

# Boolean constructor 
 
    let b1 = Boolean(12);
    console.log(b1);

    et b2 = Boolean(0);
    console.log(b2);

<hr><br><br><br><br>   

 # Logical operators

 - || - first truthy, else the last;
- && - first falsy, else the last;

<hr><br><br><br><br>

# Nullish coalescing operator ??

>First non-nullish element, else the last;

<hr><br><br><br><br>

# Conditional (ternary) operator

    condition ? expressionIfTrue : expressionIfFalse;

<hr><br><br><br><br>

# Switch case


    switch(expression) {
       case x:
       // code block
       break;
       case y:
       // code block
       break;
       default:
      // code block
    }