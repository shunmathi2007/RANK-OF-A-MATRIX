# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
#Program to find the rank of a matrix.
#Developed by: SHUNMATHI S S
#RegisterNumber: 212225040412
# Python program to find the rank of a matrix

matrix = [[1, 2, 3],
          [3, 6, 9]]

# Since second row is a multiple of first row
if matrix[1][0] == 3 * matrix[0][0] and    matrix[1][1] == 3 * matrix[0][1] and    matrix[1][2] == 3 * matrix[0][2]:
    rank = 1
else:
    rank = 2

print("", rank)

## Output:
<img width="1272" height="841" alt="Screenshot 2026-06-02 001517" src="https://github.com/user-attachments/assets/190398b2-6101-4ac8-8ce1-115c25ab16f8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

