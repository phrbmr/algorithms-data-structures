# Algorithms and Data Structures
A Full Course for Beginners from @Treehouse and @freeCodeCamp

## Table of contents

### 1- Introduction to Algorithms
#### a) Playing a Counting Game
___
* _What Is an Algorithm?_

A set of steps or instructions (a program takes) for completing a task.

The study of the body of knowledge on how to solve common problems and to identify when to apply a said algorithm (algorithm thinking).

Deep understand about complexity e efficiency 
___
* _Guess the Number_

Establish the bounds of the problem.

Any given problem there´s no one best solution. The need is to find what’s is the best strategy to the given problem based on the necessity. 
___
* _Defining an Algorithm_

An algorithm fallows a certain set of guidelines and use the same steps every time it tries to solve the problem.

An importing first step to defining an algorithm it is not the algorithm but the problem itself. An algorithm must have a clear problem statement:

  - > What´s the **input**?
  - > What´s the expected **output**?

An algorithm must have a specific **set of instructions** in a particular **order**. The steps need to be distinct, no able to be broken in further subtasks.

An algorithm should produce a **result**, so we can verify the algorithm works. This needs to be **consistent**, so given the same input, the set of instructions must produce the same output.  

An algorithm should **complete** and not take an infinite amount of time.
___
* _Evaluating an Algorithm_

There is no single way to measure if a given algorithm is the right solution because It´s all about context.

It´s possible to evaluate an algorithm based on its **Correctness** and **Efficiency**.

An algorithm is deemed **correct** if on every run against all possible values in the input data it produces the expected output. Furthermore, its also needs to, for any possible input, terminate or end. Algorithm correction can be proved by mathematical induction.

An algorithm is deemed **efficient** if helps to solve the problem faster and with better user experience. There are two measures of efficiency: **time** and **space**.

- > **Time Complexity**: how long it takes the algorithm to run
  - Best case scenario
  - Average case scenario
  - Worst case scenario – benchmark
- > **Space Complexity**: amount of memory used on the computer
___
* _Evaluating Linear Search_

Also known as sequential or simple search.
- > **Input**: series of values
- > **Output**: the position in the list of the searched number
- > **Instructions**: Start at the beginning / Compare current value to target / Move sequentially / Reach end of the list
- > **Result**: the value searched or None

We can consider the number of tries took to guess the search as an indicator of the time (running time of the Algorithm).

- > _Time Complexity_: **O(n)**

![Linear Search BigO](https://github.com/phrbmr/algorithms-data-structures/blob/a594bb054b9624790c8be54df0e17bfe59a341b6/Images/LinearSearch.png)
___
* _Evaluating Binary Search_

Binary search is an efficient algorithm for finding an item from a sorted list of items.
- > **Input**: series of values in a sorted list
- > **Output**: the position in the list of the searched number
- > **Instructions**: Start at in the middle / Compare current value to target / If too low, set the min to be one larger than the guess / If too high, set the max to be one smaller than the guess / go back to step one with the new until the target is found or the sub list contains 1 element
- > **Result**: the value searched or None

We can consider the number of tries took to guess the search as an indicator of the time (running time of the Algorithm).

- > _Time complexity_: **O(log n)**

![Binary Search BigO](https://github.com/phrbmr/algorithms-data-structures/blob/a594bb054b9624790c8be54df0e17bfe59a341b6/Images/BinarySearch.png)
___
#### b) Time Complexity
* Efficiency of an Algorithm
* Constant and Logarithmic Time
* Linear & Quadratic Time
* Quasilinear Time
* Exponential Time
* Determining Complexity
___
#### c) Algorithms in Code
* Linear Search in Code
* Binary Search in Code
* Recursive Binary Search
___
#### d) Recursion and Space Complexity
* Recursive Functions
* Space Complexity
* Recap of Algorithms in Code
___
### 2- Introduction to Data Structures
___
#### Exploring Arrays
* Introduction
* Array Basics
* Accessing a Value in an Array
* Array Search, Insert and Delete
___
#### Building a Linked List
* What Is a Linked List?
* Adding Nodes to a Linked List
* Implementing Search
* Inserting a Node
* Removing a Node
___
#### The Merge Sort Algorithm
* Merge Sort
* Splitting Into Sublists
* Recursively Merging Sublists
* Ensuring the Correctness of Merge Sort
* Evaluating the Runtime of Merge Sort
___
### Sorting a Linked List
* The Merge Function
* The Divide Step
* The Conquer Step
* Evaluating the Runtime
* Recap of Introduction to Data Structures
___
### 3- Algorithms: Sorting and Searching
___
#### Sorting Algorithms
* Sorting and Searching
* Bogosort
* Selection Sort
* Getting the Run Time of a Program
* Recursion
* Quicksort
* Implementing Quicksort
* Merge Sort
* Actual Run Time for Sorting Algorithms
* Big-O Run Times of Sorting Algorithms
___
#### Searching Names
* Linear Search
* Sorting Names
* Binary Search
* Timing Our Search Scripts
* Big O Runtime of Search Algorithms
