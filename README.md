# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End of the program

## PROGRAM:
```
#Developed by: THARUN V K
#Register Number: 212223230231

with open("text1.txt", 'r') as fp:
    msg=fp.read()
with open("copy.txt", 'w') as fp1:
    fp1.write(msg)
```
### OUTPUT:
![image](https://github.com/tharunkumaran2006/Copy-File/assets/151625188/d98cceb6-cabf-42e8-8beb-616ded6af3c6)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
