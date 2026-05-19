# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program

## Program:
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: RAJESH .S (25007890)
RegisterNumber: 
*/

import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)

(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)




## Output:
![lu decomposition]()


<img width="1132" height="548" alt="Screenshot 2026-05-19 221817" src="https://github.com/user-attachments/assets/778f1d8a-d2ad-47f1-819c-eab170ea5d18" />

<img width="1173" height="241" alt="Screenshot 2026-05-19 221834" src="https://github.com/user-attachments/assets/9ce5bb12-41f0-461a-b525-99b69bd7b984" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

