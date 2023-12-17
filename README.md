# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Use 'import numpy as np' to include NumPy for numerical operations.
### Step 2:
Create a 2x2 matrix A with elements [[2, 2], [1, 3]]. 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
~~~
PYTHON
#Program to find the eigen values and eigen vectors.
#Developed by: thenmozhi p
#RegisterNumber:23005024
import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

~~~
## Output:
![image](https://github.com/thenmozhi05/EIGENVALUES-AND-EIGENVECTORS/assets/140684207/ba0b2f30-d52e-4fae-bef0-f5bd13edee6c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
