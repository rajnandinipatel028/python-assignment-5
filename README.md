# python-assignment-5
# Python Practice Tasks

This repository contains basic Python tasks to demonstrate dictionary handling and list slicing. Each task includes a clear problem statement, solution steps, and sample output.

---

## 📝 Task 1: Create a Dictionary of Student Marks

### ✅ Problem Statement:
Write a Python program that:

1. Creates a dictionary where student names are keys and their marks are values.
2. Asks the user to input a student's name.
3. Retrieves and displays the corresponding marks.
4. If the student’s name is not found, displays an appropriate message.

### 📌 Sample Code:
```python
student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92
}

name = input("Enter the student's name: ")

if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    print("Student not found.")
output:
Enter the student's name: Alice
Alice's marks: 85
Enter the student's name: John
Student not found.


