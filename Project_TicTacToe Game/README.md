

![IMAGE](https://www.arkadium.com/arenaxstorage-blob/arenax-index/_arena-shared-content_/arkcom-game-arts/tic-tac-toe/Game_Tiles/jpeg/1000x312.jpg)


## FOLDER STRUCTURE:


| FOLDER | Description | 
| ----- | ----- | 
| 1_REQUIREMENTS | Documents detailing requirements and research |
| 2_ARCHITECTURE| Documents specifying design details |
| 3_IMPLEMENTATION | All code and documentation |
| 4_TEST PLAN | Documents with test plans and procedures|
| 5_REPORT | Report|
| 6_IMAGES AND VIDEOS | Output Images|


## DESCRIPTION


*	The first player, who shall be designated "X", has 3 possible positions to mark during the first turn. Superficially, it might seem that there are 9 possible positions, corresponding to the 9 squares in the grid. However, by rotating the board, we will find that in the first turn, every corner mark is strategically equivalent to every other corner mark. The same is true of every edge (side middle) mark.
*	 For strategy purposes, there are therefore only three possible first marks: corner, edge, or center. Player X can win or force a draw from any of these starting marks; however, playing the corner gives the opponent the smallest choice of squares which must be played to avoid losing. This might suggest that the corner is the best opening move for X, however another study shows that if the players are not perfect, an opening move in the center is best for X.
*	The second player, who shall be designated "O", must respond to X's opening mark in such a way as to avoid the forced win. Player O must always respond to a corner opening with a center mark, and to a center opening with a corner mark. An edge opening must be answered either with a center mark, a corner mark next to the X, or an edge mark opposite the X. Any other responses will allow X to force the win. Once the opening is completed, O's task is to follow the above list of priorities in order to force the draw, or else to gain a win if X makes a weak play.
