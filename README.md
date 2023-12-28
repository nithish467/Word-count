# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
 create a file with .txt file extension

### Step 2: 
 add some text in that file
 
### Step 3: 
 create a python file

### Step 4: 
 write a code to count the number of words in that file

### Step 5:
 run the program

### Step 6: 
 display the output

## PROGRAM:
## Developed by: NITHISH KUMAR S
## Reference Number: 23013506
```
def program():
    count=0
    with open("Files.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()

```
### OUTPUT:

![Screenshot (20)](https://github.com/nithish467/Word-count/assets/150232274/585642ce-109a-4275-868c-0a97daa600f1)

![Screenshot (21)](https://github.com/nithish467/Word-count/assets/150232274/6f53ce42-2880-4db0-b54b-20ef50fca4ce)


## RESULT:
Thus the program is written to find the word count from a text.
