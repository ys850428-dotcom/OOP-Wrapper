# OOP Wrapper – Employee Management System

## Description
A Python console application that demonstrates Object-Oriented Programming (OOP) concepts including classes, inheritance, encapsulation, method overloading, method overriding, `super()`, and `issubclass()`.

## Features
- Create Person, Employee, Manager, and Developer objects.
- Private attributes with getter/setter methods (encapsulation).
- Method overriding in derived classes.
- Simulated method overloading using default arguments.
- Demonstrate `issubclass()` and `isinstance()` checks.
- Constructor and destructor methods.
- Menu-driven interface with input validation.

## Assumptions
- Employee ID is a string (e.g., 'E123').
- Salary is a float.
- Age is an integer.
- Method overloading is simulated using default arguments.
- Data is not persisted to disk.

## Class Hierarchy
Person
└── Employee
├── Manager
└── Developer

## How to Run
1. Ensure Python 3.x is installed.
2. Clone the repository.
3. Run: `python employee_management_system.py`

## Sample Output
============================================================
Welcome to the Employee Management System!
============================================================
This program demonstrates OOP concepts: classes, inheritance,
encapsulation, method overloading, method overriding, super(),
and issubclass().

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 1

--- Create a Person ---
Enter Name: John Doe
Enter Age: 30
Person created with name: John Doe and age: 30.

Person created with name: John Doe and age: 30.

--- Choose another operation ---

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 2

--- Create an Employee ---
Enter Name: Jane Smith
Enter Age: 28
Enter Employee ID: E123
Enter Salary: 50000
Person created with name: Jane Smith and age: 28.

Employee created with name: Jane Smith, age: 28, ID: E123, and salary: $50000.0.

--- Choose another operation ---

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 3

--- Create a Manager ---
Enter Name: Alice Johnson
Enter Age: 40
Enter Employee ID: M456
Enter Salary: 80000
Enter Department: Sales
Person created with name: Alice Johnson and age: 40.

Manager created with name: Alice Johnson, age: 40, ID: M456, salary: $80000.0, and department: Sales.

--- Choose another operation ---

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 5

--- Show Details ---
Choose details to show:
1. All Objects
2. Persons Only
3. Employees Only
4. Managers Only
5. Developers Only
Enter your choice: 1

----------------------------------------

[Person Details]
Name: John Doe
Age: 30
----------------------------------------

[Employee Details]
Name: Jane Smith
Age: 28
Employee ID: E123
Salary: $50000.0
----------------------------------------

[Manager Details]
Name: Alice Johnson
Age: 40
Employee ID: M456
Salary: $80000.0
Department: Sales
----------------------------------------

--- Choose another operation ---

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 6

--- OOP Concepts Demonstration ---

1. issubclass() Checks:
   issubclass(Employee, Person)   -> True
   issubclass(Manager, Employee)  -> True
   issubclass(Manager, Person)    -> True
   issubclass(Developer, Employee)-> True
   issubclass(Person, Employee)   -> False

2. Encapsulation Demonstration:
   Employee 'Jane Smith' salary via getter: $50000.0
   After setter (+$5000): $55000.0

3. Method Resolution Order (MRO):
   Manager MRO: ['Manager', 'Employee', 'Person', 'object']
   Developer MRO: ['Developer', 'Employee', 'Person', 'object']

4. isinstance() Checks:
   John Doe: isinstance(obj, Person) = True
   Jane Smith: isinstance(obj, Person) = True
   Alice Johnson: isinstance(obj, Person) = True

--- Choose another operation ---

==================================================
--- Python OOP Project: Employee Management System ---
==================================================
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Demonstrate OOP Concepts
7. Exit
==================================================
Enter your choice: 7

Exiting the system. All resources have been freed.
Goodbye!
Person object for John Doe has been deleted.
Employee object for Jane Smith has been deleted.
Person object for Jane Smith has been deleted.
Manager object for Alice Johnson has been deleted.
Employee object for Alice Johnson has been deleted.
Person object for Alice Johnson has been deleted.

## Author
Suraj
