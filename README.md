# Task_01_FSD60WD-E_28-05-24
Task_01_FSD60WD-E_28-05-24-Introduction to Browser &amp; web


Q1) Write a blog on Difference between HTTP1.1 vs HTTP2
answer:
HTTP1.1
1) In  HTTP1.1 the actual page load speed to a degree was not possible.
2) HTTP1.1 loads resources one after the other, so if one resource cannot be loaded, it blocks all the other resources behind it. 
3) Due to loading resources one after the other, it would take more time and there was no binary-code messages.
4) In HTTP1.1 small files load more quickly than the larger ones.
HTTP2
1) HTTP2 allows to maximize preceived and actual page load speed.
2) HTTP2 is able to use a single TCP connection to send multiple streams of data at once so that no resource blocks each other.
3) http 2 used splitting data into binary-code messages and numbering these messages so that client knows which stream each binary message belongs to.
4) HTTP2 uses a more advanced compression method called HPACK thateliminates redundant information in HTTP header packets.

Q2) Write a blog about objects and its internal representation in Javascript
answer:
In JavaScript, almost "everything" is an object. All JavaScript values, except primitives, are objects.
With JavaScript, you can define and create your own objects.

There are different ways to create new objects:

Create a single object, using an object literal.
Create a single object, with the keyword new.
Define an object constructor, and then create objects of the constructed type.
Create an object using Object.create().
Using an Object Literal
This is the easiest way to create a JavaScript Object.

Using an object literal,
Define and create an object in one statement.

An object literal is a list of name:value pairs (like age:50) inside curly braces {}.

The following example creates a new JavaScript object with four properties:

Example
const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
