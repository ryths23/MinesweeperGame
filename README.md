# MINESWEEPER

-Minesweeper is a single-player puzzle video game. The objective of the game is to clear a rectangular board containing hidden "mines" or bombs without detonating any of them, with help from clues about the number of neighbouring mines in each field.

-Working of app :-
 The app containes 2 activities- MainActivity as launcher activity and GameActivity.
 1. The main activity displays the user his best game time and last game time.
    The user has the option to choose from following levels :-
     a) Easy - This levels has 9 rows, 9 columns and 20 mines.
     b) Medium - This levels has 16 rows, 16 columns and 63 mines. This level is selected by default.
     c) Hard - This levels has 30 rows, 16 columns and 119 mines.
     d) Custom - In this level, user chooses the number of rows, columns and mines in the game.
    The number of mines is always less than 1/4th of the board’s buttons to avoid overcrowding of mines.
    