# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: praveen v
#RegisterNumber:212222233004
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are", values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-11-17 201008](https://github.com/praveenv23013808/EIGENVALUES-AND-EIGENVECTORS/assets/145824728/989c5c19-13f7-429e-9da9-c29596208a65)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
