# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
Open the file and assign it to f1

### Step 3:
Read the file and assign it to data

### Step 4:
Split the data (data.split())

### Step 5:
Print the assigned variable's length using len(word)

### Step 6:
End the program

## PROGRAM:
```python
# Developed by : SANJAY M
# Register No  : 212223230187

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is ",len(word))
f1.close()
```
### OUTPUT:
![alt text](<Screenshot 2024-05-12 093121.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
