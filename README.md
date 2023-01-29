Read-from-CSV
AIM:
To write a python program for reading content from a CSV file.
ALGORITHM:
Step 1:
Import pandas as pd.
Step 2:
Read the CSV file using read_csv method.
Step 3:
Use head and tail method to get the required contents from the file.
Step 4:
Use len() method to get the number of rows and columns.


## PROGRAM:
# Developed by: G.suji
# Register Number: 22008563
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
### OUTPUT:
![f2](https://user-images.githubusercontent.com/119559822/215304401-0482a278-2566-411d-bf06-60b95b332473.png)
![f3](https://user-images.githubusercontent.com/119559822/215304408-57ed65b2-98ad-4340-829d-d043057e3ab9.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
