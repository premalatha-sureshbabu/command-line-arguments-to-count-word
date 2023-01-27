# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
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
```
Developed by : S.Premalatha
Register number : 22009393
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()        
```

### OUTPUT:

![Screenshot (87)](https://user-images.githubusercontent.com/120620842/215146287-a61379eb-6a37-46b1-af5a-15ec1a38e1d7.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
