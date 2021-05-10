## Problem 1
(Palindrome)
Write a program that checks whether an integer is a palindrome.

For eample, 121 and 131 are palindromes. However, 123 is not a palindrome.

[Answer](https://github.com/minyoungrho/DailyCodingProblems/blob/main/answers/palindrome.ipynb)

## Problem 2
($\pi$)

Write a program that approximates $\pi$. 

Hint:
1. Use a unit circle (and its area formula).
2. Use random number generator for a uniform distribution.

[Answer](https://github.com/minyoungrho/DailyCodingProblems/blob/main/answers/pi.ipynb)


## Problem 3
Create a function "build_tree" that accepts ona parameter which is the number of lines of the tree. 

Example: build_tree(6) builds the following tree:

        *
        * *        
        * * *        
        * * * *        
        * * * * *        
        * * * * * *
        
Condition: There can only be one "*" in the code.

Hint: Use "\n" for line breaks and print result to see it in tree form instead of: "*\n**\n***\n****\n*****\n******\n"


If you liked it you can also try to create another function (build_tree_reverse) which builds the tree in a reverse way:
    
        * * * * * *
        * * * * *  
        * * * *        
        * * *        
        * *        
        *
        
Remember to use only one "*".


And finally you can create another function combining the previous functions to create an arrow. 

        *
        * *
        * * *
        * * * *
        * * * * *
        * * * * * *
        * * * * *
        * * * *
        * * *
        * *
        *

Here 2 "*" are allowed.


## Problem 4

Given two **integers**, create a function that finds **the largest prime** within the range of the two integers.

All numbers should be positive integers.

Example: an input of (2, 10) results in 7
