# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library
### Step 2: Get the matrix elements from the user and store them in a NumPy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors of the matrix as the output.

## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np


a = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])
              

eigenvalues, eigenvectors = np.linalg.eig(a)


print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
## Output:
<img width="1319" height="397" alt="image" src="https://github.com/user-attachments/assets/1041ab69-bb4a-49a6-8123-cf02400cc078" />
<img width="1302" height="370" alt="image" src="https://github.com/user-attachments/assets/eba581bc-dec5-4ba2-8a2a-5236802b0052" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
