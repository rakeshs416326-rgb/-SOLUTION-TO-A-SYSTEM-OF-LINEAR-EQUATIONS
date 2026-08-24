# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
# Linear Algebra Exp 1
```
Write a program to find a solution to a system of linear equations
5x-3y-10z=-9, 
2x+2y-3z=4, 
-3x-y+5z=-1
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)

```


## Output:
<img width="1046" height="641" alt="image" src="https://github.com/user-attachments/assets/f297e542-842c-49ce-9048-19f8bc6f3d46" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

