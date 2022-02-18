# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator. We assume that words in a sentence are separated by a space character.
### Step 4:  
The length of the split list should equal the number of words in the text file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
#Developed by : A K MOHAN RAJ
#Reference no :21001890

num_of_words = 0
file = open('wordtext.txt')
wordtext = file.read()
words = wordtext.split()
num_of_words = len(words)
print("Number of words = ",num_of_words)

```

### OUTPUT:
![git log](s2.jfif)
![](s.jfif)

## RESULT:
Thus the program is written to find the word count from a text.
