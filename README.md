# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: create a matrix usins np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: get the output and end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Nirosha M
#RegisterNumber: 23014438
import numpy as np
a = np.array([[2,2],[1,3]])
values,Vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```

## Output:
![image](https://github.com/niroshamuthukumar/EIGENVALUES-AND-EIGENVECTORS/assets/151830921/dc01348a-0fe0-4946-a3b0-3d30f93cab8f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
