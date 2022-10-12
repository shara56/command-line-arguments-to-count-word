# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
 
### Step 2:
Open file using commandline arguments.
 
### Step 3: 
Using for loop find the word count from the contents of a file.

### Step 4: 
Use len to count number of words.

### Step 5: 
Give print statement.

### Step 6: 
End the program.

## PROGRAM:    
 ```python
#Developed by:sharangini k
#Registration no:22003363
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word = line.split()
        count+= len(word)
print("World Count in File = ",count) 
```
### OUTPUT:
![Screenshot from 2022-10-12 14-47-05](https://user-images.githubusercontent.com/113497104/195303263-dba34dfc-acae-46cf-a518-7e2fb9d97e2b.png)
![Screenshot from 2022-10-12 14-46-04](https://user-images.githubusercontent.com/113497104/195303314-6ee74c54-a86d-4644-8982-ec63e2646f46.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
