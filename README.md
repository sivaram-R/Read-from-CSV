# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file

## ALGORITHM:
###Step 1:
Import pandas as pd.

###Step 2:
Read the CSV file using read_csv method.

###Step 3:
Use head and tail method to get the required contents from the file.

###Step 4:
Use len() method to get the number of rows and columns

###Step 5:
Print the output
## PROGRAM:
##student name:sivaram R
<br>
##reference no:22008680
```
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print("Number of rows:",len(f.axes[0]))
print("Number of columns:",len(f.axes[1]))
```
## OUTPUT:
![Screenshot from 2023-01-26 10-36-27](https://user-images.githubusercontent.com/121165794/214763208-89304c77-d4ce-4fa4-993c-e6a14020e0bc.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
