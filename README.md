# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
Register No:2305002025
Developed By:Subha shree U
1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
![image](https://github.com/subha2406/Norm-of-a-matrix/assets/155226504/9cfd671c-f493-4f02-a852-5c669211ee7f)
![image](https://github.com/subha2406/Norm-of-a-matrix/assets/155226504/47cb462b-3988-4559-8177-3714c269ca07)
![image](https://github.com/subha2406/Norm-of-a-matrix/assets/155226504/502b4b18-f3a7-4d5c-b880-543e3b18f3cd)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
