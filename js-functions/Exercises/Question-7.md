What is the error in this code?

```javascript

function getResult(num1,num2,num3){
 console.log(num1-num2+num3)
}
 
getResult(2,3,4,5);
 
Output:

No error. Even though an extra parameter (5) is passed, the function getResult simply does not use it.	

```
