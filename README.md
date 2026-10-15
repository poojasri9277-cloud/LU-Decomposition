# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## 5(A)
1. Start the program and import the required NumPy and SciPy libraries
2. Define the given square matrix A
3. Use the LU decomposition function to find the lower triangular matrix L and upper triangular matrix U
4.Display the matrices L and U ,and verify the result by checking A = LU. 

## Program:
## 5(A) To find the L and U matrix
### Program to find the L and U matrix.
### Developed by: 
### RegisterNumber: 
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np 
### from scipy.linalg import lu
### a = np.array(eval(input()))
### P,L,U=lu(a)
### print(L)
### print(U)

## 5(B) To find the LU Decomposition of a matrix
### Program to find the LU Decomposition of a matrix.
### Developed by: 
### RegisterNumber: 
### import os 
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve
### a = np.array(eval(input()))
### b = np.array(eval(input()))
### l,p=lu_factor(a)
### x=lu_solve((l,p),b)
### print(x)


## Output:
## 5(A)
<img width="745" height="777" alt="image" src="https://github.com/user-attachments/assets/a3fdebf8-6391-4b98-851b-337dd849b22f" />
## 5(B)
<img width="647" height="608" alt="image" src="https://github.com/user-attachments/assets/bb758ec1-3088-4b57-8199-3e950c59b45d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

