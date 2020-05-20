# Group_D_Gomoku

## Project Statement
Gomoku, also called Five in a Row, is an abstract strategy board game. It is traditionally played with Go pieces (black and white stones) on a Go board. It can be played using the 15×15 board or the 19×19 board. Players alternate turns to place a stone of their colour on an empty intersection. The winner is the first player to form an unbroken chain of five stones.

![Gomoku - Wikipedia](data:image/png;base64,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)



## Functions

## How to use it

