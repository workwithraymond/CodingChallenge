<h1>Write a function that takes an array of numbers and returns the sum of the numbers. The numbers can be negative or non-integer. If the array does not contain any numbers then you should return 0.</h1>

<h2>Question 1</h2>
// Sum Numbers
function sum (numbers) {

}

Solution 1 :

// Sum Numbers
function sum (numbers) {
    return numbers.reduce((a, b) => a + b, 0);
}

Solution 2 :

// Sum Numbers
function sum (numbers) {
    "use strict";
    let result = 0;
    for(let i=0;i<numbers.length;i++){
      result += numbers[i];
    }
    return result;
};