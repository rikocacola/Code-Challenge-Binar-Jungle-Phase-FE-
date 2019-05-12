# Code-Challenge-Binar-Jungle-Phase-FE-

JS Code Challenge

    1. What is the value of foo?
    var foo = 10 + '20';

The value is : 1020


    2. What will be the output of the code below?
    console.log(0.1 + 0.2 == 0.3);

output on the console will be 'false'


    3. How would you make this work?
    add(2, 5); // 7
    add(2)(5); // 7

add(2,5); // 7
var add = function(a,b) {
return a + b;
};

add(2)(5); // 7
var add = function(a) {
return function(b) {
return a + b;
}};


    4. What value is returned from the following statement?
    "I'm a lasagna hog".split("").reverse().join("");

Reverse a String With Built-In Functions
the value is :
“goh angasal a m\'i”


    5. What is the value of window.foo?
    ( window.foo || ( window.foo = "bar" ) );

the value is “bar”


    6. What is the outcome of the two alerts below?
    var foo = "Hello";
    (function() {
        var bar = " World";
        alert(foo + bar);
    })();
    alert(foo + bar);

the outcome is two alert, 
the first one is : Hello World
the second one is error, because bar is not defined.


    7. What is the value of foo.length?
var foo = [];
foo.push(1);
foo.push(2);

the value of foo.length is 2
foo.length = 2


    8. What is the value of foo.x?
    var foo = {n: 1};
    var bar = foo;
    foo.x = foo = {n: 2};

the value of foo.x is undefined



    9. What does the following code print?
    console.log('one');
      setTimeout(function() {
      console.log('two');
     }, 0);
     console.log('three');

one, three, two
