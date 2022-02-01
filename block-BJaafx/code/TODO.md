1. Using loops take 10 inputs from user and find the average of all the numbers.

  function userAverage() {
 let sum = 0;
 let avg = 0;
 for (let i = 0;i < 10;i++ ){
 let userinput = +prompt("Enter a inputs");
 sum += userinput;
 }
 avg = sum/10;
 return avg;

 }
userAverage();

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
/// error println is not  a defined  function
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(max=10){
  let sum = 0;
  for(let i =0; i<=max ; i++){
    if(i%2==0){

      sum = sum+i;
    }
  }
  return sum;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.


function getOddSum(max=10){
  let sum = 0;
  for(let i =0; i<=max ; i++){
    if(i%2!==0){

      sum = sum+i;
    }
  }
  return sum;
}
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

function getProductOfDigits(num)
{
  let product = 0;

  while (num!=0){
        product = product * (num % 10);

        num = num / 10;
  }
 return product; 
}
6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger than 5
check(1); // Smaller than 5
check(5); // return  5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'.
getOutput('John'); // 'You are john'.
getOutput(); // 'Who are you' .
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'.
getOutput('John'); // 'You are john'.
getOutput(); // 'Who are you' .
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

No a  function can execute a single return statement 
But you  can use multiple return statement in  the if else block but it will allso execute only one of them.




10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

 /* The difference between for loop and while loop is that in for loop the number of iterations to be done is already known and is used to obtain a certain result whereas in while loop the command runs until a certain condition is reached and the statement is proved to be false. *?
