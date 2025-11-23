# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="1080" height="130" alt="image" src="https://github.com/user-attachments/assets/f1431c9a-60b7-48d1-9646-fa4c86e917f5" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="787" height="112" alt="image" src="https://github.com/user-attachments/assets/3bd45750-a894-498c-b443-32c9a2d5551f" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="891" height="587" alt="image" src="https://github.com/user-attachments/assets/7d1729a7-06b6-4252-b72d-7fe7d06b6d87" />

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="707" height="155" alt="image" src="https://github.com/user-attachments/assets/71ef07c0-013a-4018-85ca-8483b6df18ea" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="637" height="97" alt="image" src="https://github.com/user-attachments/assets/89c014a7-547b-4e7a-bd1b-d4ab888fd400" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="582" height="111" alt="image" src="https://github.com/user-attachments/assets/5f98c27c-2c56-47c1-9487-0eef7efdf597" />



## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="702" height="321" alt="image" src="https://github.com/user-attachments/assets/eaa2a45a-03c2-47a6-bfd5-e9c0d7fbc5a6" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="572" height="493" alt="image" src="https://github.com/user-attachments/assets/8fd0bb19-f779-42c5-a20e-27aef3f4ca35" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt
<img width="830" height="343" alt="image" src="https://github.com/user-attachments/assets/dce0dbb9-eb5c-4c9a-b7ca-da7cc1fc9768" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT
<img width="657" height="163" alt="image" src="https://github.com/user-attachments/assets/a25b104c-d448-4789-82df-d59d7a551b7f" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="918" height="417" alt="image" src="https://github.com/user-attachments/assets/436bf6fa-4e6b-4929-aa1b-7e51baed8148" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


## OUTPUT
<img width="690" height="326" alt="image" src="https://github.com/user-attachments/assets/eec21d1f-9a5c-47e4-bcfe-dab7ee4d6811" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="743" height="177" alt="image" src="https://github.com/user-attachments/assets/9abef56f-e77a-4d89-abe6-bd83475c4882" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="676" height="711" alt="image" src="https://github.com/user-attachments/assets/d0dd9be1-2f28-44c5-bc20-1227e0157fb9" />



# RESULT:
The commands/batch files are executed successfully.

