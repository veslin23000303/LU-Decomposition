# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: VESLIN ANISH
RegisterNumber:212223240175
import numpy as np
from scipy.linalg import  lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: VESLIN ANISH
RegisterNumber:212223240175 
'''Program to solve a matrix using LU decomposition.
Developed by: VESLIN ANISH
RegisterNumber: 212223240175
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:

![WhatsApp Image 2024-04-16 at 15 31 57_9df49fc8](https://github.com/veslin23000303/LU-Decomposition/assets/151148539/1f048754-a4dc-4fd3-bf9e-a291aa28ac4b)
![WhatsApp Image 2024-04-16 at 15 32 08_6620877c](https://github.com/veslin23000303/LU-Decomposition/assets/151148539/db843b71-38dd-469b-b54d-6a9a91efa36e)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

