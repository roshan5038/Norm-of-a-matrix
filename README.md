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
# Register No:212225240124
# Developed By:Roshan V 
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 1)

print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 2)

print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, np.inf)

print("{:.2f}".format(norm))




```
## Output:
<img width="1280" height="824" alt="image" src="https://github.com/user-attachments/assets/ea12141a-783f-4b10-a9b7-4d9132056ab9" />


### 2-Norm of a Matrix
<img width="1420" height="869" alt="image" src="https://github.com/user-attachments/assets/67418e0d-6ee4-45f6-bf1e-318382ab898f" />

### Infinity Norm of a Matrix
<img width="1264" height="840" alt="image" src="https://github.com/user-attachments/assets/02a6d6b5-b90f-4a35-967a-cd76086aafd3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
