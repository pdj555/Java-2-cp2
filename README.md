# Class Notes Week 4

### terminology
- subclass = child class
- superclass = parent class

#### java.lang.Object superclasses
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Object.html

#### java.util.ArrayList
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/ArrayList.html

#### stick with private

## Inheritance
Occurs when a class is derivaed from another class
- the derived class inheriets the class members of the parent class
- the methods of the parent class can be used in the child class
<img width="458" alt="Screen Shot 2022-09-16 at 11 54 33 PM" src="https://user-images.githubusercontent.com/102199778/190841081-abf1c039-c5a0-444d-a87a-6ea17433606c.png">
Inheriets the rectangle class members

## Polymorphism
- data types determine which program behavior to execute
Objects of a parent class are required to have the parameters of the parent class; however, the objects will be of one of the child classes. Aka upcasting.
<img width="437" alt="Screen Shot 2022-09-16 at 11 55 41 PM" src="https://user-images.githubusercontent.com/102199778/190841121-c25f03d5-749a-4457-acd6-0ace24cf618c.png">
Shape can be any of the shape classes

## Abstract methods
- not implimented in the base class
- for objects you must impliment abstract methods 

## Down casting
- first: ensure it is of a specific shape
- second: downcast

**When to do downcasting:**
- to use specific features of child class

