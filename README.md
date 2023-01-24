# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:22008663
# Developed By: R.Vidhyadharan
# 1-Norm of a Matrix
~~~py
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
~~~

# 2-Norm of a Matrix
~~~py
'''
Program to find 2-norm of a matrix.
Developed by: R.Vidhyadharan
RegisterNumber: 22008663
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
~~~


# Infinity Norm of a Matrix
~~~py
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
~~~
```
## Output:
### 1-Norm of a Matrix
![1-NOrm](/1-norm.png)

### 2-Norm of a Matrix
![2-Norm](/2-norm.png)

### Infinity Norm of a Matrix
![infinity-Norm](/infinity-norm.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
