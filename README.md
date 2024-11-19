# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/user-attachments/assets/f8f35e3e-256c-4e87-a4a3-d986a3a999a8)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/7772ec41-df9c-413f-8bbd-2b8687553d13)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/55532b80-746c-4b60-9b51-f85f58892dba)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/8510aa6b-0b31-4415-8a64-fef2e8fcb015)


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/346a1cd7-6dd2-4635-9018-bdc6a67c9a1e)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```
## OUTPUT

![image](https://github.com/user-attachments/assets/50e4ff0e-115a-4d0d-bf2d-bc6a853b1136)

# RESULT:
The commands/batch files are executed successfully.
