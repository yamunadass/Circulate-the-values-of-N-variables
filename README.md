# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
User concatention operation display the entire rotated list  
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Yamuna M
#RegisterNumber:23005405
def circulate():
    list=eval(input())
    n=int(input())
    result=list[n:]+list[:n]
    print("After circulating the values are:",result)
    
```
## Output:
![output](./circulating-1.png)

## Result:
Thus the program executed successfully.