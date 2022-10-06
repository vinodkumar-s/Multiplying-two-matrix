## AIM: To write a python program for multiplying two matrix.

## ALGORITHM:

### Step 1: 
Import Numpy as np.
### Step 2: 
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4: 
Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.

## PROGRAM: 
## Developed by: s.vinod kumar
## Register no: 22004903

```python
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
array1=np.array(l1)
array2=np.array(l2)
product=(array1*array2)
print("Product of two arrays is:",product)


```

## OUTPUT:
![output](/output.png)

## RESULT:
Thus the program is written to perform multiplying-two-matrix using python programming.



