# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array(
3. Using the np.linalg.lu(), we get two results (first is L and second is
 U) of the given matrix.
4. Using the np.linalg.lu_factor() and np.linalg.lu_solve(), we get the solution
5.  End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: yuvan raj R
RegisterNumber: 25014899
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: yuvan raj R
RegisterNumber: 25014899
*/

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
![lu decomposition]()


<img width="1161" height="441" alt="Screenshot 2025-10-17 102514" src="https://github.com/user-attachments/assets/4cfc7679-3328-4cbf-9ec3-595cfb026670" />


<img width="880" height="180" alt="Screenshot 2025-10-17 102556" src="https://github.com/user-attachments/assets/137517c4-f403-4c3d-9214-ea8694f5c094" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

