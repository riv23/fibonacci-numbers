# Fibonacci numbers

Write a function that generates and returns the n-th fibonacci number.

From [Wikipedia](https://en.wikipedia.org/wiki/Fibonacci_number):

> In mathematics, the Fibonacci numbers are the numbers in the following integer sequence, called the Fibonacci sequence, and characterized by the fact that every number after the first two is the sum of the two preceding ones.

These are the first 8 fibonacci numbers:

```
0, 1, 1, 2, 3, 5, 8, 13, ...
```

Therefore `fibonacci(8)` should dynamically calculate and return the value 13.

## Further - iterative vs recursive

Every algorithm can be implemented iteratively _and_ recursively. One approach may be more suitable than the other in most situations, but it's still feasible to implement both.

If you implemented an iterative algorithm, now try to write a recursive implementation.

Conversely, if you implemented a recursive algorithm, now try to write an iterative implementation.

## Further - dynamic programming

For a recursive implementation, ensure that your algorithm can finish executing `fibonacci(100)` in under 1 second. 

If it takes way longer than that, google for "dynamic programming" and try and implement a recursive algorithm that uses dynamic programming to execute `fibonacci(100)` in under 1 second.