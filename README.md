# task-5
Python Lists, Tuples, Sets, and Dictionaries
📌 Project Description

This project demonstrates Python's four built-in collection data structures: Lists, Tuples, Sets, and Dictionaries. It covers common operations such as adding, removing, searching, accessing, and updating elements.

🎯 Objective

To develop practical skills in handling structured data using Python collections and understand the differences between these data structures.

🛠️ Technologies Used
Python – Programming language
Jupyter Notebook – Interactive environment for writing and executing Python code
📚 Topics Covered
Lists: Creating, accessing, appending, removing, and sorting elements
Tuples: Creating and accessing immutable collections
Sets: Managing unique elements and performing set operations
Dictionaries: Storing key-value pairs and accessing, updating, and deleting values
✨ Features
Examples of all four Python collection types
Programs demonstrating common collection methods
Searching, adding, removing, and updating elements
Comparison of Lists, Tuples, Sets, and Dictionaries
Practical examples using student and employee datasets
📂 Suggested Datasets
Student Dataset
Employee Dataset
🚀 Getting Started
Prerequisites

Make sure Python is installed on your system. You can also install Jupyter Notebook to run the programs interactively.

Installation
Clone or download this repository.
Navigate to the project directory.
Install Jupyter Notebook if needed:
bash
pip install notebook

Start Jupyter Notebook:
bash
jupyter notebook

Open the project notebook and run the code cells.
💻 Example
python
# List example
fruits = ["apple", "banana", "orange"]
fruits.append("mango")
fruits.remove("banana")
print("List:", fruits)

# Tuple example
colors = ("red", "green", "blue")
print("Tuple:", colors)

# Set example
numbers = {1, 2, 3, 3, 4}
print("Set:", numbers)

# Dictionary example
student = {
    "name": "Rahul",
    "age": 20,
    "course": "Python"
}
student["age"] = 21
print("Dictionary:", student)

📊 Comparison of Collection Types
Feature	List	Tuple	Set	Dictionary
Syntax	[]	()	{}	{key: value}
Ordered	Yes	Yes	No guaranteed order	Yes (insertion order)
Mutable	Yes	No	Yes	Yes
Duplicates	Allowed	Allowed	Not allowed	Keys must be unique
Access	Index	Index	Membership	Key
🎓 Learning Outcomes

After completing this project, you will be able to:

Understand the characteristics of Python collection data structures.
Perform common operations on lists, tuples, sets, and dictionaries.
Select the appropriate collection type for different programming tasks.
Work with structured data using practical examples.
