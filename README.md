# Aim: To study and implement Recursion
# Software Required:
Visual Studio
# Theory:
Recursion is a programming technique where a function calls itself repeatedly until a specific base condition is met. A function that performs such self-calling behavior is known as a recursive function, and each instance of the function calling itself is called a recursive call.

<ins>Recursive Function</ins>:
A function that calls itself is called a recursive function. When a recursive function is called, it executes a set of instructions and then calls itself to execute the same set of instructions with a smaller input. A recursive function should contain,
Recursive Case: Recursive case is the way in which the recursive call is present in the function.
Base Condition: The base condition is the condition that is used to terminate the recursion.

<ins>Applications of Recursion</ins>:

Recursion has many applications in computer science and programming. Here are some of the most common applications of recursion:

Solving: Fibonacci sequences, Factorial Function, Reversing an array, Tower of Hanoi.
Backtracking: It is a technique for solving problems by trying out different solutions and undoing them if they do not work. Recursive algorithms are often used in backtracking.
Searching and Sorting Algorithms: Many searching and sorting algorithms, such as binary search and quicksort, use recursion to divide the problem into smaller sub-problems.
Tree and Graph Traversal: Recursive algorithms are often used to traverse trees and graphs, such as depth-first search and breadth-first search.
Mathematical Computations: Recursion is also used in many mathematical computations, such as the factorial function and the Fibonacci sequence.
Dynamic Programming: It is a technique for solving optimization problems by breaking them down into smaller sub-problems. Recursive algorithms are often used in dynamic programming.

# Implementation:
The concept of recursion was understood by the following codes,
+ Factorial using recursion
+ sum of integers using recursion
+ reversal of string and integers using recursion

# Algorithms:

Algorithm: Reverse a String Using Recursion

1. Start
2. Declare a character array `ch[50]`.
3. Prompt the user to *"Enter a string"* and read input into `ch`.
4. Define a recursive function `rev(char* str)`:
   1. If `*str` is not null (`\0`):
       Call `rev(str + 1)` recursively.
        Print the current character `*str`.
5. In `main()`, call `rev(ch)` to display the reversed string.
6. End


Algorithm: Reverse an Integer Using Recursion

1. Start
2. Declare an integer variable `a`.
3. Prompt the user to *"Enter the number"* and read input into `a`.
4. Define a recursive function `revint(int a)`:
   1. If `a > 0`:
      * Print `a % 10` (the last digit of `a`).
      * Call `revint(a / 10)` recursively (removing the last digit).
5. In `main()`, call `revint(a)` to display the number in reverse.
6. End

Algorithm: Sum of First n Natural Numbers Using Recursion

1. Start
2. Declare an integer variable `n` and another variable `a` for storing the result.
3. Prompt the user to *"Enter a number"* and read input into `n`.
4. Define a recursive function `add(int n)`:
   1. If `n <= 1`, return 1.
   2. Else, return `n + add(n-1)` (sum of `n` and the sum of first `n-1` numbers).
5. In `main()`, call `add(n)` and store the result in `a`.
6. Display the value of `a`.
7. End

Algorithm: Factorial Using Recursion

1. Start
2. Declare an integer variable `x` and another variable `A` to store the factorial.
3. Prompt the user to *"Enter the number"* and read input into `x`.
4. Define a recursive function `fact(int x)`:
   1. If `x <= 1`, return 1.
   2. Else, return `x * fact(x-1)` (multiply `x` by factorial of `x-1`).
5. In `main()`, call `fact(x)` and store the result in `A`.
6. Display `"The factorial is : "` followed by `A`.
7. End
# Concusion:
The above codes demonstrate the concept of recursion in C++
