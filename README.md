## LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
  
 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Pavithra S
RegisterNumber:212223230147
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)


```

## Output:
![Screenshot 2024-04-28 150216](https://github.com/pavithraselvaraj30/LU-Decomposition/assets/149366880/ead90781-4a47-4225-ac98-7e9d12bff424)

![Screenshot 2024-04-28 150358](https://github.com/pavithraselvaraj30/LU-Decomposition/assets/149366880/2af6f3e0-d374-4864-af2c-500c6d405f11)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

