# Letter-Square-Solver
Self-Implemented Letter Square Solver(Using Recursive Backtracking technique)

The New York Times includes a daily puzzle called “Letter Boxed.” It involves a set of 12 letters arranged around the sides of a square, 

such as the following:
![S](https://user-images.githubusercontent.com/92423096/168499197-85f44c9c-333d-40f0-a443-090a5afed42b.png)

To solve the puzzle, you need to come up with a sequence of English words in which each letter in the puzzle appears at least once. 

In addition, the words in the sequence must observe the following constraints:

Each word must be at least 3 letters long.

Adjacent letters must come from different sides of the square. For example, when solving the puzzle above, 

if the first letter in a word is T, the second letter in that word cannot be either A or E, since A and E are on the same side of the square as T.

One word that can be formed from the puzzle above is TIME. I is on a different side of the square than T, M is on a different side than I, 

and E is on a different side than M.

The last letter of one word of the sequence must match the first letter in the next word in the sequence. For example, 

if we use TIME as the first word in our solution, the second word must then begin with E, since TIME ends with E.

For a given puzzle, there are many possible solutions, but solutions that use fewer words are preferred. 

For the puzzle above, one possible solution is

 LIMES 
 STONES
 SHAKY

However, an even better solution is
 MILESTONES
SHAKY

because it uses fewer words.
