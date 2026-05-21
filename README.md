# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries such as NumPy and SciPy.
2. Use the scipy.linalg.lu() function to perform LU Decomposition of the given matrix.
3. Create the matrix using the np.array() function.
4. Create the matrix using the np.array() function.

## Program:
(i) To find the L and U matrix
~~~
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
~~~

## Output:
<img width="843" height="165" alt="math e 5 2" src="https://github.com/user-attachments/assets/9601621c-fde4-46f5-8ef8-7c62614d2379" />


```
/*
Program to find the L and U matrix.
Developed by: MONISH V
RegisterNumber: 212225220066
*/
```
(ii) To find the LU Decomposition of a matrix:

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition]()
<img width="843" height="165" alt="math e 5 2" src="https://github.com/user-attachments/assets/93479109-a6fc-4e84-93cf-5f208e635808" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

