Project Description
This is a command-line interface (CLI) application that allows users to interact with a file system using a set of defined commands. The application supports commands for navigating directories, creating and deleting files and directories, and modifying file permissions, among others.

The command interpreter is built using Python 3 and can be run on any platform with Python installed. The application has a simple and intuitive command-line interface that makes it easy for users to navigate and interact with the file system.

How to Start the Command Interpreter
To start the command interpreter, first clone the repository to your local machine. Once you have the repository on your machine, navigate to the project directory in your terminal and run the following command:

How to Use the Command Interpreter
The command interpreter supports a set of commands that can be used to interact with the file system. The following is a list of supported commands:
python3 main.py
This will start the command interpreter and you should see a prompt that looks like this:
$>


ls - list files and directories in the current directory
cd - change the current directory
mkdir - create a new directory
touch - create a new file
rm - delete a file or directory
chmod - change the permissions of a file or directory
help - display the help message
exit - exit the command interpreter
To use a command, simply enter it at the prompt and press enter. Some commands may require additional arguments, such as the name of a file or directory. For example, to create a new directory named my_dir, you would enter the following command:
$> mkdir my_dir

Examples
The following are some examples of how to use the command interpreter:

To list the files and directories in the current directory:
$> ls
file1.txt
file2.txt
dir1
To create a new file named new_file.txt:
$> touch new_file.txt
To delete the file named old_file.txt:
$> rm old_file.txt
To change the permissions of a file named file.txt to read-only:
$> chmod 400 file.txt
Authors
Taddele Ejigu taddele@gmail.com
