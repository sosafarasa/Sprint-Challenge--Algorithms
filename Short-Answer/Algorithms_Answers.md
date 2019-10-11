#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), because time will increase in direct proportion of n


b) O(n^2), because there are 2 O(n) operations ^^^


c) O(n), refer to a

## Exercise II
 
 I would solve it using Binary Search which has a time complexity of O(n).
 1- Start by dividing n/2 to find the middle
 2- compare the middle to f 
    - if middle == f: return f
    - if  middle > f: then we know f is if not in this half
    - if middle < f: repeat n/2 on this half until middle == f

