# Graph 3D GUI
A multivariate function plotting graphic user interface using Matlab App Designer <br />

<img src="https://github.com/yyydky/graph_3d_gui/blob/master/demo.gif" width="600" height="300">

## Usage:
1. Download the entire folder and open in Matlab.
2. Run graph_3d.mlapp.
3. Enter the following numeric inputs for the x value, the starting point, the step, and the ending point. The y input is the transpose of x .
4. Enter the formula containing x and y variables.
4. Users can click the contour checkbox to see the contour plot.
5. Press the plot button.

## Error Handling:
Inappropriate x input: 
- Step input cannot be zero. 
- Only numeric data is allowed (int/double)
- The step input is signed. Please make sure the sign of the step agrees with the direction from the starting point to ending point given.

<img src="https://github.com/yyydky/graph_3d_gui/blob/master/input_err.png" width="600" height="300">

Inappropriate formula input: 
- Please make sure the formula containing only two variables, x and y.

<img src="https://github.com/yyydky/graph_3d_gui/blob/master/fcn_err.png" width="600" height="300">

## Environment:
MATLAB_R2020b
