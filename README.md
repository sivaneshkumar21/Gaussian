# RANK-OF-A-MATRIX

~~~
Name: SIVANESH KUMAR .N
Register No: 212225240149
~~~

## Aim:

To write a python program to find the rank of a matrix

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

### Algorithm:

### Step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program

## Program:

Write a program to find the rank for the given matrix [[5,-3,-10],[2,2,-3],[-3,-1,5]]

~~~
A = [[5, -3, -10],
     [2,  2,  -3],
     [-3, -1,  5]]

det = (A[0][0]*(A[1][1]*A[2][2] - A[1][2]*A[2][1])
     - A[0][1]*(A[1][0]*A[2][2] - A[1][2]*A[2][0])
     + A[0][2]*(A[1][0]*A[2][1] - A[1][1]*A[2][0]))

if det != 0:
    print(3)
else:
    print(2) 
~~~

## Output:

<img width="337" height="164" alt="2" src="https://github.com/user-attachments/assets/146c1fd9-f938-4709-a5bc-4b34f712f69a" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

