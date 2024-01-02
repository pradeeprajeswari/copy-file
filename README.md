# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End the program.
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : PRADEEP E
# RegisterNumber:212223230149
with open("basic.txt","r") as f:
    x=f.read()
with open("basic1.txt","w") as f1:
    f1.write(x)
```

### OUTPUT:
![Screenshot 2024-01-02 083739](https://github.com/pradeeprajeswari/copy-file/assets/145743112/316eb884-5ce4-4c23-b17d-1c67fad042ff)

![Screenshot 2024-01-02 083749](https://github.com/pradeeprajeswari/copy-file/assets/145743112/f3be58e6-cc66-4952-a70f-50815c8f0535)

![Screenshot 2024-01-02 083757](https://github.com/pradeeprajeswari/copy-file/assets/145743112/aee75161-7afa-443b-9529-798d52e136aa)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
