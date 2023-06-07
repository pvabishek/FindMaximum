# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: P.V.Abishek
RegisterNumber: 212222230003
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:P.V.Abishek 
RegisterNumber: 212222230003
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: P.V.Abishek
RegisterNumber:212222230003 
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max



```
## Sample Input and Output
) 

## Output:
![Screenshot 2023-06-07 074311](https://github.com/pvabishek/FindMaximum/assets/119405626/6df06e42-6be0-40ba-9275-9a3e3fd12545)

![Screenshot 2023-06-07 074329](https://github.com/pvabishek/FindMaximum/assets/119405626/6d7c9907-64bf-416f-a003-b69dc7ec399c)

![Screenshot 2023-06-07 074343](https://github.com/pvabishek/FindMaximum/assets/119405626/e0e2f94e-d58f-46db-b5af-f97d6a0895ab)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
