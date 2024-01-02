# Read-from-CSV

## AIM:
To write a python progrom to import content from a csv file
## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using read_csv
### Step 3:
Use head and tail methods to get required content from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output
## PROGRAM:
```
#Program to read the contents of a CSV file
#Developed by: Shehan Shajahan
#Register Number: 23008724
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-02 201049](https://github.com/shehanshajahan/Read-from-CSV/assets/139317389/f29925ad-5867-4ece-982b-3df9df5d0f53)
## RESULT:
Thus a Python program is written to read the contents of a CSV file
