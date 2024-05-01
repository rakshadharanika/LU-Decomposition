# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import necessary packages such as scipy.linalg import lu.








2.Get input from user and print L and U matrix by 'print'.








3.Create the variable as 'X' include the package in that variable.








4.Print the variable 'X'.





## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: RAKSHA DHARANIKA V 
RegisterNumber: 212223230167

```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```



(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: RAKSHA DHARANIKA V
RegisterNumber: 212223230167

```
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![Screenshot (131)](https://github.com/rakshadharanika/LU-Decomposition/assets/149348380/43329f0c-3298-4005-a24e-cc100dab5568)
![Screenshot (132)](https://github.com/rakshadharanika/LU-Decomposition/assets/149348380/efe7b275-9d6f-4d2d-bb2d-6659c6cc70d6)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

