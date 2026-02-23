# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the appropriate command, we can find the solutions.

Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Rougith D
RegisterNumber: 25017014
*/

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Rougith D
RegisterNumber: 25017014
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
L and U matrix





<img width="625" height="757" alt="image" src="https://github.com/user-attachments/assets/28a086e9-fa55-489c-8101-213677cda8d0" />

LU Decomposition of a matrix





<img width="507" height="574" alt="image" src="https://github.com/user-attachments/assets/241601d9-eab8-4fdc-bfba-97581448bd8b" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

