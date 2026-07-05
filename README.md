# Gyan-Richard-inheritance-
University of Mines and Technology Management System

Project Overview

This project is a simple Object-Oriented Programming (OOP) application written in Python. It demonstrates the use of core OOP concepts such as classes, inheritance, method overriding, constructors, and objects by modeling a basic management system for the University of Mines and Technology (UMaT).

The system consists of a parent class (Person) and two child classes (Student and Lecturer), allowing student and lecturer information to be stored and displayed.

⸻

Features

* Create a general Person with a name and age.
* Create a Student with:
    * Student ID
    * Enrolled course
    * Enrollment function
* Create a Lecturer with:
    * Employee ID
    * Course being taught
    * Teaching function
* Demonstrates inheritance using the Person class.
* Demonstrates method overriding through the display_info() method.
* Uses super() to access parent class methods and constructors.

⸻

Object-Oriented Programming Concepts Used

1. Class

The program defines three classes:

* Person
* Student
* Lecturer

2. Inheritance

Both Student and Lecturer inherit attributes and methods from the Person class.

3. Encapsulation

Each object stores its own data using instance attributes such as:

* name
* age
* student_id
* employee_id
* enroll_course
* teach_course

4. Method Overriding

The display_info() method in both child classes overrides the parent method while still calling the parent’s implementation using super().

5. Objects

Two objects are created:

* Gyan (Student)
* Matthew (Lecturer)

⸻

Project Structure

University Management System
│
├── Person
│   ├── name
│   ├── age
│   └── display_info()
│
├── Student (inherits Person)
│   ├── student_id
│   ├── enroll_course
│   ├── enroll()
│   └── display_info()
│
└── Lecturer (inherits Person)
    ├── employee_id
    ├── teach_course
    ├── teach()
    └── display_info()

⸻

Sample Output

========================================
        STUDENT INFO
========================================
Name: Gyan
Age: 20
Student ID: FOE.41.006.088.25
Course: Electrical and Electronic Engineering
Gyan has enrolled in Electrical and Electronic Engineering
========================================
        LECTURER INFO
========================================
Name: Matthew
Age: 39
Employee ID: LE_27
Teaching: Object Oriented Programming
Matthew is teaching Object Oriented Programming

⸻

Requirements

* Python 3.x

No external libraries are required.

⸻

How to Run

1. Save the Python code in a file (for example, management_system.py).
2. Open a terminal or command prompt.
3. Navigate to the project directory.
4. Run the program using:

python management_system.py

⸻

Learning Objectives

This project helps learners understand:

* Python classes and objects
* Constructors (__init__)
* Inheritance
* Method overriding
* The super() function
* Creating and using objects
* Organizing code using Object-Oriented Programming principles

⸻

Author

Richard Gyan

Department of Electrical and Electronic Engineering

University of Mines and Technology (UMaT)

⸻

License

This project is created for educational purposes and may be freely modified and used for learning Object-Oriented Programming in Python.
