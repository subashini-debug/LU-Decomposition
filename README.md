# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import numpy 

2. Import lu from scipy.linalg

3. Get the inputs using numpy.array

4. Use the function lu() to find the L and U matrices

## Program:
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: Subashini K
RegisterNumber: 212225240160
*/

```

import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix
```

/*
Program to find the LU Decomposition of a matrix.
Developed by: Subashini K
RegisterNumber: 212225240160
*/

```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,piv=lu_factor(A)

X=lu_solve((lu,piv),B)

print(X)
```
## Output:
(i) To find the L and U matrix



<img width="1920" height="1080" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/1a02315b-0b1f-4475-b573-268eaeda30d3" />

<img width="1920" height="1080" alt="Screenshot (234)" src="https://github.com/user-attachments/assets/b5e985c4-a9b8-455a-b9cf-2c058650847d" />


(ii) To find the LU Decomposition of a matrix





<img width="1920" height="1080" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/64c24ec6-dacb-463f-898d-24cc47f8fedb" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

