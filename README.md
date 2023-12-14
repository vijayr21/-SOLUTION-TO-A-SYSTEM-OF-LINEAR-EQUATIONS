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
```
#Program to find the solution for the given linear equations.
#Developed by: VIJAY R
#RegisterNumber:23013759
import numpy as np
A =[[1,3],[2,5]]
b =np.array([5,-3])
c = np.linalg.solve(A,b)
print(c)
```

## Output:
![Screenshot 2023-12-14 102914](https://github.com/vijayr21/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149347607/396664cb-2beb-463c-87e5-b85cb03be994)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

