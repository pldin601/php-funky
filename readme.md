# php-funky
Functional Library for PHP.

Consist of two parts - Option and Lambda.

## Option
Option is an object that represents encapsulation of an optional value. It can be used as the return value of functions which may or may not return a meaningful value when they are applied.
It has two subclasses - Some and None. First encapsulates the original data and the second if there is no data to encapsulate. 

## Lambda
Lambda is a tool which helps you to make short callback functions for using, for example, in map, filter, sort or reduce callbacks.

Example 1. Will return sum of numbers from 1 up to 5:

```php
$sum = array_reduce(range(1, 5), func("$ + $"), 0);
```
