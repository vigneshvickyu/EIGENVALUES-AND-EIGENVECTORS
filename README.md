# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
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
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: VIGNESH M
#RegisterNumber:23014020
import numpy as np
A=[-2,2,-3],[2,1,-6],[-1,-2,0]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
![image](https://github.com/vigneshvickyu/EIGENVALUES-AND-EIGENVECTORS/assets/151948835/33786099-ecf5-47fe-bbdd-c33aa02fc2f0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
