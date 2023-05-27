# Python-Cheat-Sheet
Python cheat sheet that includes some commonly used syntax and concepts.

Basic Syntax:

Print: print("Hello, World!")
Comments: # This is a comment
Variables: x = 5
Data Types: int, float, string, boolean, list, tuple, dictionary
Control Flow:

Conditional Statements:

python
Copy code
if condition:
    # Code block
elif condition:
    # Code block
else:
    # Code block
Loops:

For loop:

python
Copy code
for item in iterable:
    # Code block
While loop:

python
Copy code
while condition:
    # Code block
Functions:

Defining a Function:

python
Copy code
def function_name(parameters):
    # Code block
    return result
Calling a Function:

python
Copy code
result = function_name(arguments)
Data Structures:

Lists:

python
Copy code
my_list = [1, 2, 3, 4]
Tuples:

python
Copy code
my_tuple = (1, 2, 3, 4)
Dictionaries:

python
Copy code
my_dict = {"key": "value", "name": "John"}
File Handling:

Reading a File:

python
Copy code
file = open("filename.txt", "r")
content = file.read()
file.close()
Writing to a File:

python
Copy code
file = open("filename.txt", "w")
file.write("Hello, World!")
file.close()
Libraries:

Importing Libraries:

python
Copy code
import library_name
Using Specific Functions from a Library:

python
Copy code
from library_name import function_name
Error Handling:

Try-Except Block:
python
Copy code
try:
    # Code block
except ExceptionType:
    # Code block to handle the exception
Miscellaneous:

Getting User Input:

python
Copy code
user_input = input("Enter your name: ")
Length of a List or String:

python
Copy code
length = len(my_list)
String Concatenation:

python
Copy code
combined_string = string1 + string2
This cheat sheet covers some basic Python syntax and concepts. Remember to refer to the official Python documentation and additional resources for a more comprehensive understanding of the language.
