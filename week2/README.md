# The Master Method, Quicksort, and Probability

## Optional Theory Problems
1. Give the best upper bound that you can on the solution to the following recurrence: T(1)=1 and T(n)≤T([√n])+1 for n>1. (Here [x] denotes the "floor" function, which rounds down to the nearest integer.)

2. You are given an n by n grid of distinct numbers. A number is a local minimum if it is smaller than all of its neighbors. (A neighbor of a number is one immediately above, below, to the left, or the right. Most numbers have four neighbors; numbers on the side have three; the four corners have two.) Use the divide-and-conquer algorithm design paradigm to compute a local minimum with only O(n) comparisons between pairs of numbers. (Note: since there are n2 numbers in the input, you cannot afford to look at all of them. Hint: Think about what types of recurrences would give you the desired upper bound.)

My idea for this was find something small in the middle and sort of descend downwards with the gradient. One method that fits these constraints would be to find the minimum number in the middle row and column and roll downwards with the steepest gradient.