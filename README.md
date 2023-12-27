# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the solution.
### Step 4: 
End the program.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: vignesh raaj s
#RegisterNumber:23005346
import numpy as np
matrix = np.array([[1,2,3],[3,6,9]])
rank = np.linalg.matrix_rank(matrix)
print(f"{rank}")
```
## Output:
![Screenshot 2023-11-29 225157](https://github.com/vigneshraaj00/RANK-OF-A-MATRIX/assets/138849113/cad49f38-11ef-408a-aab3-9d9a096c0c6a)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

