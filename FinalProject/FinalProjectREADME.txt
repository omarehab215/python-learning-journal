To run the program, you need to execute the python file using the command
python Battleship.py

After running the game, the program will print out a 2-dimensional array that will represent your board.
    The symbol '0' will represent a square occupied by a ship and the symbol '~' will represent an empty square
Below the board, the program will ask you if you like the ship arrangement on the board.
    Will ask you to input either "y" if you want to continue or "n" if you want a new ship arrangement.
After that, the game will begin and you will take turns with the computer opponent at hitting the opponent's ships.
On your turn, the program will ask you to input a coordinate with a letter from A to H to represent the vertical coordinate and a number 1-8 to represent horizontal coordinate.
    The coordinate will have to begin with the letter followed by a comma and then the number (eg: A,6)
    If the attempt landed on the same square as an opponent's ship, the board will mark it as 'H' to represent a hit and give the player another turn
    If the attempt landed on an empty square, the board will mark that square as an 'X' to indicate a miss
The game will continue until one player's ships are all destroyed and the remaining player wins the game
