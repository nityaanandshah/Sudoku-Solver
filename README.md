# Sudoku-Solver
I have used basic recursion to make a cpp program to solve Sudoku. 
Since we have to fill the empty cells with available possible numbers and we can also have multiple solutions,
the main intuition is to try every possible way of filling the empty cells. 
And the more correct way to try all possible solutions is to use recursion.
In each call to the recursive function, we just try all the possible numbers for a particular cell and transfer the updated board to the next recursive call.
Time Complexity: O(9(n ^ 2)), in the worst case, for each cell in the n2 board, we have 9 possible numbers.
Space Complexity: O(1), since we are refilling the given board itself, there is no extra space required, so constant space complexity.
Source - take U forward (Recursion)
