Minesweeper Game

Overview

This is a simple Minesweeper game built using Python and the Tkinter library. The game generates a grid with hidden mines and allows players to uncover safe squares or flag potential mines. The goal is to reveal all non-mine squares without triggering a mine.

Features

Randomly generated mines on a 10x15 grid.

Left-click to reveal a square.

Right-click to flag a suspected mine.

A counter displays the number of remaining mines.

A win message when all non-mine squares are revealed.

A game-over message when a mine is triggered.

How to Play

Run the script to start the game.

Click on any square:

If it's a mine, the game ends.

If it's safe, a number appears showing how many mines are adjacent.

Right-click to flag a square as a suspected mine.

Continue revealing squares until all non-mine squares are uncovered to win.

Requirements

Python 3

Tkinter (included in standard Python installations)

How to Run

Install Python if not already installed.

Save the script as minesweeper.py.

Run the script using:

python minesweeper.py

Code Structure

mine_grid(): Generates the grid and places mines.

reveal_square(): Uncovers a square and checks for mines.

add_flag(): Allows players to mark suspected mines.

reveal_mine(): Handles game-over scenario when a mine is clicked.

count_adjacent_mines(): Counts the number of mines surrounding a revealed square.

check_win(): Checks if the player has won the game.

update_mines_left_label(): Updates the mine counter display.

License

This project is for educational purposes and can be modified freely.
