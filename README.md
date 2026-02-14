# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array() 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: MOHAMED SHIAF N
#RegisterNumber: 25018427
import numpy as np
x = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
y = np.linalg.matrix_rank(x)
print(y)

```
## Output:
<img width="818" height="602" alt="Screenshot 2026-02-14 084937" src="https://github.com/user-attachments/assets/65defd33-13f6-4e8d-92d3-65a85db3b558" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

