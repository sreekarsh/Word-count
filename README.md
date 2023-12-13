Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
Step 1:Create a file with .txt file extension.
Step 2:Add some texts in that file.
Step 3:Create a python file.
Step 4:Write a code to count the number of words in that file.
Step 5:Run the program.
Step 6:Display the output.
## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```
## OUTPUT:
![image](https://github.com/sreekarsh/Word-count/assets/139841918/5e8d1bce-bd62-456b-8ebc-a4d5b38f8c82)

![image](https://github.com/sreekarsh/Word-count/assets/139841918/d3c33e0a-cd60-4deb-a290-eed47b16f268)



## RESULT:
Thus the program is written to find the word count from a text.



## RESULT:
Thus the program is written to find the word count from a text.
