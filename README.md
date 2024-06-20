# 8-puzzle-game
An 8 puzzle is a simple game consisting of a 3 x 3 grid (containing 9 squares). One of the squares is empty. The object is to move to squares around into different positions and having the numbers displayed in the "goal state"



1. Import Necessary Libraries.
<br>
import numpy as np<br>
import math<br>
import time
<br>
<br>
2. Define the Start and Goal States.
<br>
start = np.array([4, 1, 3, 7, 2, 5, 8, 0, 6]).reshape(3, 3)<br>
goal = np.array([1, 2, 3, 4, 5, 6, 7, 8, 0]).reshape(3, 3)
<br>
<br>
3. Define the Functions to generate possible Moves.
<br>
def actions_array(array)
<br>
<br>
4. Define the Heuristic Function.
<br> 
def h_value(array)
<br>
<br>
5. Define the Main Function.
<br>
def main()
<br>
<br>
6. Execute main.