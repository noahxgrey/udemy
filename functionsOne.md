# Introduction to Functions

### Functions let us wrap bits of code up into REUSABLE packages. 

#### Declare a function first
```javascript
function doSomething() {
    console.log("HELLO WORLD");
}
// then call it:
doSomething();
```

## Arguments
### Often we want to write functions that take inputs.
```javascript
function square(num) {
    console.log(num * num);
}
// now when we call square we need to pass in a value
square (10); //prints 100
square(3); //prints 9
square(3); //prints 16

//ex:
function sayHello(name) {
    console.log("Hello there " + name + "!");
}

sayHello(Noah); //Hello there Noah!
```

### Functions can have as many arguments as needed
```javascript
function area(length, width) {
    console.log(length * width);
}
area(9,2); //18

function greet(person1, person2, person3) {
    console.log("hi " + person1);
    console.log("hi " + person2);
    console.log("hi " + person3);
}
greet("Noah", "Ivy", "Chandler"); 
//hi Noah
//hi Ivy
//hi Chandler
``` 
