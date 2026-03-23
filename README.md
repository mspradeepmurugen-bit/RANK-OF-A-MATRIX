# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  Import the numpy module to use the built-in functions for calculation
### Step 2:  Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Pradeep.M
#RegisterNumber:212225220071
import numpy as np
A=np.array([[5,3,-10],[2,2,-3],[-3,-1,5]])
X=np.linalg.matrix_rank(A)
print(X)
```
## Output:
<img width="1127" height="184" alt="Screenshot 2026-03-23 212847" src="https://github.com/user-attachments/assets/58b99a3e-c641-4510-aa6a-b8659553edfe" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

