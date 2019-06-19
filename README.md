# battleship_kata
Enjoy the classic board game through TDD

It's a 2 player game 

Each player has a board of 10x10 rows being marked as letters from A to J and columns marked as numbers from 1 to 10.

In each player's board all fleet must be inside the board

Board must have fleet containing:
1 Carrier for a total of 5 squares
1 Battleships for a total of 4 squares
2 Submarine for a total of 3 squares
1 Destroyer for a total of 2 squares

Each player takes a turn calling a shot referring to a square
If a square is already discovered, player recalls shot
If a square contains no ship other player must say miss
If a square is occupied by a ship other player must say hit and ship type
If a ship is hit in all its positions other player must say sunk

Game ends when either player sinks opponents fleet



