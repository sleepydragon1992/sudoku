# sudoku
Sudoku puzzle generator by backtracking recursion algorithm. The algorithm used a random number between 1 to 9 for each recursive call to randomize the puzzle. 

To generate puzzle, numbers are removed from a full solution one by one, at each steps the code check for uniqueness of the solution. Once a sudoku puzzle generate more than one solution, the algorithm undo the last removal and keep this as the puzzle. 

Currently user has only 2 options: Ask for a hint or getting the completed solution. Further improvement will be required of there's interest: 

4x4, 16x16 Sudoku

User interface to change number at blank location 

Point system 


To start the game, make sure you have Rust installed. Simply use command "cargo run" from inside the cargo in terminal. Use "ctrl + c" to exit
