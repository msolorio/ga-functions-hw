![ga-logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

## Setup

Fork and clone this repo to your local computer. Inside the repo, an `index.html` file and an `app.js` file. Connect your JavaScript file to your HTML file with a script tag. Write your answers in `app.js`.

## 1. Verbal questions

Write answers to the following questions as comments. 

1. What is the difference between a _parameter_ and an _argument_?
2. Within a function, what is the difference between _return_ and _console.log_?
3. What would the benefit be of having a function _return_ a value rather than using a _console.log_?

<br>

---

## 2a. SEI Rocks

Write a function called `printSeiRocks` that logs to the console, `'SEI Rocks!'`.

For example, calling the function like so...
```js
printSeiRocks();
```
would log to the console...
```js
'SEI Rocks!'
```

<br>

---

## 2b. SEI Rocks Again

Write a function called `saySeiRocks` that _returns_ the value, `'SEI Rocks!'`. (Note this time, the function should not log anything to the console. Instead it should _return_ a value)

For example
```js
const message = saySeiRocks();

console.log(message);
// => 'SEI Rocks!'
```

<br>

---
## 3a. Add One

Write a function called `addOne` that takes a single number as an parameter and logs to the console that number plus 1.

For example, calling the function like so...
```js
addOne(1);
```
would log to the console...
```js
2
```

<br>

---

## 3b. Add One Again

Write a function called `addOneAgain` that takes a single number as an parameter and _returns_ that number plus 1. (Note this time, our function would not log anything to the console. Instead we're having our function return a value)

For example
```js
const sum = addOneAgain(1);

console.log(sum);
```

Bonus Challenge: If the argument passed in is not a number, return `NaN`.

<br>

---

## 3. Say Hello

Write a function called `sayHello` that takes two parameters, a `name` and a `hometown` and _returns_ the greeting to the console, "Hello, I am <name> and I hail from <hometown>".

For example

```js
const greeting = sayHello('Jon', 'Winterfell');

console.log(greeting);
```

<br>

---
## 4. Get the First Item

Write a function called `getFirstItem` that takes in an array as an parameter, and _returns_ the first item from that array.

Example:
```
const firstItem = getFirstItem(['apple', 'banana', 'orange']);

console.log(firstItem);
// => 'apple'
```

Bonus Challenge: See if you can write a function `getLastItem` that takes an array as an argument and returns the last item in the array.

<br>

---

## 5. Check Day

Write a function called `checkIfFriday` that takes a day of the week as a parameter. The function should _return_ `true` if the day of the week is 'Friday'. Otherwise it should return `false`.

For example
```js
const currentDay = 'Tuesday';

console.log(checkIfFriday(currentDay));
// => false
```

```js
const currentDay = 'Friday';

console.log(checkIfFriday(currentDay));
// => true
```

<details>
    <summary>Hint:</summary>

    You will want to use a conditional statement. (An if / else statement)
</details>

<br>

---

## 6. Get Lowercase

Write a function called `getLowerCase` that takes in a string as parameter and _returns_ that string converted to lowercase. Try googling 'javascript convert a string to lowercase'.

For example
```js
const lowerCaseFruit = getLowerCase('Apple');

console.log(lowerCaseFruit);
// => 'apple'
```

```js
const libraryMessage = getLowerCase('SHHHHH, INSIDE VOICES');

console.log(libraryMessage);
// => 'shhhhh, inside voices'
```

### You made it! You finished the homework!

## CSS
Watch the following three videos on CSS:

- [First CSS video - 5 minutes](https://www.youtube.com/watch?v=xWiT2TWCFjc&index=3&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J)
- [Second CSS video - 11 minutes](https://www.youtube.com/watch?v=UMMHsQPmfug&index=4&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J)
- [Third CSS video - 17 minutes](https://www.youtube.com/watch?v=g0Aq2kP5-CY&index=5&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J)

<br>

---

## Hungry for More?
Here are some extra optional challenges to work through if you are hungry for more.

## Palindrome
Write a function `checkPalindrome` that accepts a single argument, a string. Later in this assignment we're gonna beef up our palindrome function some. The function should return true if the string is a palindrome, false if not. A _palindrome_ is a word that is the same spelled backwards and forwards, for example: Racecar. Make sure your function will give the correct answer for words with **capital letters**.

```javascript
const wordIsPaindrome = checkPalindrome("Radar");

console.log(wordIsPaindrome);
=> true
```

```javascript
const wordIsPaindrome = checkPalindrome("Cat");

console.log(wordIsPaindrome);
=> false
```

<br>

---

## Check a List

Write a function `checkForStudent` that takes 2 parameters, a student's name and an array of students, and checks if the student's name is in the array. If the student's name is included in the array the function should return true. If the name is not included in the array the function should return false.

```js
const studentIncluded =  checkForStudent('Sally', ['Sally', 'Kyle']);

console.log(studentIncluded);
=> true
```

```js
const studentIncluded =  checkForStudent('Ron', ['Sally', 'Kyle']);

console.log(studentIncluded);
=> false
```

<br>

---

## Sum Array

Write a function `sumArray` that takes an **array** as an argument.
The array should contain numbers. The function should return the sum of the numbers in the array.

**Try solving it using a loop instead of using [`.reduce()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)**.

Expected result:
```javascript
const sum = sumArray([1, 2, 3, 4, 5, 6]);

console.log(sum);
=> 21
```

<br>

---

## Still Hungry for More?

## Digit Sum
Write a function `sumDigits` that accepts a number and returns the sum of its digits.
```js
const sum = sumDigits(42);

console.log(sum);
=> 6;
```

## Pythagoras
Write a function `calculateSide` that takes two arguments: `sideA` and `sideB`, and returns the solution for sideC using the Pythagorean theorem.

_hint:_ discover the Pythagorean Theorem on a website called google.com

_hint:_ checkout the [Math methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) in javascript

**For this problem, do not use `Math.hypot()`**
```js
const sideC = calculateSide(8, 6);

console.log(sideC);
=> 10
```

## Prime Numbers
A Prime number is a number that is not evenly divisible by another number except 1 and itself. If you want to read more deeply about it, [go here](https://en.wikipedia.org/wiki/Prime_number).
To test whether a number is Prime, you only need to test as far as the **square root** of that number. This is advisable for optimization and testing large numbers.

### Step One
Write a function called `checkPrime` that will test whether a number is Prime. The function will return true (Boolean) if Prime, false if not.
_Hint:_ Check every number up to the square root. To do this, try a _for loop_.

### Step Two
Write another function called `printPrimes` that will print (console log) all the Primes up to an arbitrary limit. For example, if you invoke your function with `printPrimes(97)`, it will print all the Prime numbers up to and including 97.
This function can **call on** the previous `checkPrime` function.

## Insert Dash

Write a function `insertDash` that accepts a number as a parameter and returns a string with a dash inserted between any consecutive **odd numbers**. There should not be a dash at the end, it goes only between numbers.
```javascript
const numWithDashes = insertDash(454793);

console.log(numWithDashes);
=> 4547-9-3
```

## Reverse a String

Write a function `reverseString` that takes a string as a parameter and returns that string with the letters reversed **without using `.split()`, `.reverse()`, or `.join()`**.

4. Make your palindrome function from problem two above work regardless of spacing (or capitalization). So, for example, "Sit on a potato pan Otis" or "Bird rib" would pass the test.

5. Make your palindrome function work even if the string contains punctuation.  So: "Sit on a potato pan, Otis!!!" or "A man, a plan, a canal: Panama." or "Cigar? Toss it in a can! It is so tragic." would pass the test.

6. Make a "word palindrome" function that returns true if the words in a phrase are the same backwards and forwards.  It should not care about spacing, capitalization, or punctuation.  For example the following string would pass the test: 

    "Son, I am able," she said. "Though you scare me, watch!" said I, "Beloved," I said, "watch me scare you!" Though, said she: "able am I, son."

7. You still want more?!?! Do you even sleep? Create an account on [Project euler](https://projecteuler.net/archives) and keep working on those problems.

## More Practice

For more practice with functions, check out the website, [Codewars](https://www.codewars.com/). Codewars is a code challenge platform with hundreds of challenges of different difficulty levels. Create an account, start on the easiest difficulty level, and slowly work your way up.
