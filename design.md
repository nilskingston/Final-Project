# Tic Tac Toe

## Design Specification

The design specificaiton is a counterpart to the Functional Speciffication. Where a functional specification concerns itself
with inputs and outputs from the program, or the *experience* of a user running the program, the design specification is concerned with decisions that the engineer and programmer must make during its creation.

The design specification should include information like:

This game runs on http://runpython.com.  I used Python 3 to write my program.  The user will choose their spot on the tic tac toe board by pressing one of the assigned letters on their keyboard. These keys are layed out at the beggining of each game.  Those keys are then assigned to numbers through a dictionary and the numbers are what the program reads as where the spot on the board is.  The program alternates between X and O each time asking the user where they would like to go.  After each turn, the program checks to see if the game is over.  It starts in the x direction.  It checks to see if their is piece (of the player that just went) in the beggining of the first row and if there is it checks each spot in the first row.  If not it moves on the the second row and does the same.  And then the third row.  If none of that leads to the end of the game, the program moves onto the y direction.  It follows a similiar formula of checking the first spot in each row and only goes on the chech subsequent spots if that player's piece exits at the beggining of that row.  Then the program quickly checks the two diagnols.  Its also worth noting that the program will check to see if all the spots are filled which would also lead to the end of a game.  If any of these tests are True, then the game will end and the program will print "Game is over"

The most notibale algorithims are the ones used to check for "game over" in the x and y directions.

* What tools or frameworks will you use to build the project (e.g. http://runpython.com or ggame)?
* What language will you use for coding (usually Python 3)?
* For every element of the Functional Specification, what code will need to be written to support it?
* What data will be stored or manipulated by the program? How will it be encoded and organized?
* Describe the logic and/or code behind every interaction with the user, and behind everything displayed.
* If your program uses an unusual or notable *algorithm*, what is the algorithm and how does it work?
