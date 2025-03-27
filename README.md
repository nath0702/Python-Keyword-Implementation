Employee Payroll System

## Description
The **Employee Payroll System** is a Python program that allows users to manage employee records, including adding, removing, viewing employees, and processing payroll. The system also calculates net salaries after tax deductions and provides additional deductions for each employee. It includes error handling, file saving functionality, and utilizes Python keywords meaningfully throughout the implementation.

## Features
- **Add Employee**: Add a new employee with a name and salary.
- **Remove Employee**: Remove an employee using their unique employee ID.
- **View Employees**: Display all employees along with their salaries and net pay.
- **Process Payroll**: Calculate and display payroll details, including deductions.
- **Save Employee Data**: Store employee records in a file.
- **Generate Payroll Report**: Use a generator function to yield employee salary details.
- **Error Handling**: Handles invalid inputs and exceptions gracefully.

## Python Keywords Used
This program effectively uses all the required Python keywords:

### Control Flow Keywords
- `if`, `elif`, `else`: Used in menu selection and salary validation.
- `for`, `while`: Used in loops for iterating through employees.
- `break`: Used to exit the main menu loop.
- `continue`: Used to handle invalid inputs and continue execution.
- `try`, `except`, `finally`: Used for error handling in payroll processing and input validation.

### Function and Class Keywords
- `def`: Defines functions such as `add_employee`, `remove_employee`, `process_payroll`, etc.
- `class`: Defines the `Employee` class to represent employees.
- `return`: Returns calculated net salary.
- `lambda`: Used to define a short function for tax deduction.
- `yield`: Used in the `generate_report()` function to return employee details lazily.

### Object-Oriented Programming Keywords
- `self`: Refers to instance variables in the `Employee` class.
- `assert`: Ensures salary input is greater than zero.
- `global`: Allows access to the global `employees` list inside functions.
- `nonlocal`: Not used directly but could be used in nested functions for variable scope.
- `del`: Deletes an employee record from the list.

### Boolean and Special Values
- `True`, `False`: Used in conditions to control the loop execution.
- `None`: Represents the absence of a value in some cases.

### Importing Modules
- `import`: Used to import `random` for generating unique employee IDs.
- `from`: Used to specify module imports (e.g., `from random import randint`).

### Exception Handling and File Operations
- `raise`: Used to raise an error if salary input is invalid.
- `with`: Used in file handling to save employee records.

## How to Run the Program
1. Ensure you have Python installed (Python 3.x recommended).
2. Save the script as `payroll_system.py`.
3. Run the script using `python payroll_system.py`.
4. Follow the on-screen prompts to add, remove, view, and process payroll for employees.

## File Output
- The program creates a file `employees.txt` to store employee details.
- The payroll report is displayed in the console.

## Conclusion
This **Employee Payroll System** demonstrates a structured approach to Python programming while effectively utilizing all the required Python keywords. The program is user-friendly and can be expanded with additional features such as exporting reports to CSV, adding roles, and more advanced tax calculations.

