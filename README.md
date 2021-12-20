# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. from the given values,import numpy as np.
2. use scientific python build on extension for calculating decompostion.
3. mark 'A' as eval input.
4. write p,l,u = lu(A)
5. print L and U.

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Naveenkumar.S
RegisterNumber: 21500481
*/
import numpy as np
from scipy.linalg import lu
A= eval(input())
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![output_qstn1](./LU1st.PNG)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

