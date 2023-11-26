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
```Python
def max_marks(marks):
    return(max(marks))


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max        


```


## Output:
i) # To find the maximum of marks using the list method sort.
![Screenshot 2023-11-26 153852](https://github.com/subikshan2006/FindMaximum/assets/139841805/e21bc6bc-2352-4aa5-9e7c-d6a691979377)

ii) # To find the maximum marks using the list method max()
![Screenshot 2023-11-26 153859](https://github.com/subikshan2006/FindMaximum/assets/139841805/71ce3476-3496-4a16-a25c-cb47afc89201)

iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-11-26 153906](https://github.com/subikshan2006/FindMaximum/assets/139841805/b8219d65-d1e6-41cb-8af6-fe26c7f6f107)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
