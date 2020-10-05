# A Basic Calculator Using Python (GUI Based)
## This task was assigned as classed work.

**This assignemt was completed using various basic GUI features of Python. This model is perfect for understanding how the basic GUI features work in Python using PyQt5.QtWidgets.**

Basic in this mini project we're focusing on five main modules. whichwe are going to discuss in detailed.
    1. test.py
    2. view.py
    3. controller.py
    4. model.py
    5. main.py 
    

## 1. test.py
**Create a file  test.py and import required packages from PyQt5.QtWidgets.**

    - Now, make an application using QApplication()
    - Give dimensions of the output window according to your choice by using QWidget().
    - Print a hello message (Checking for window whether it is working or not) and then end the window using show().


## 2. view.py 
**Create view.py, import Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into test.py from PyQt5.QtWidgets.**

    - Now, create class GUI which calls constructor of QMainWindow.
    - Using different widget and layout functions, define the calculator's look and layout as needed.
    - Create a display bar at top for showing the entered digits in a calculator.
    - Now using tuples, define position of each and every button in the calculator layout.
    - Construct the grid layout of buttons perfectly.

##  3. main.py
**Create main.py.**

    - Define the main function.
    - Create and call an instance of QApplication.
    - Show the GUI using GUI() and show() methods.

## 4. model.py
**Create model.py and add the following in the module.**

    - Define evaluateExpression method in it.
    - Pass the expression in the above listed method and check whether it throws any exception or not, if not then print the result.

## 5. controller.py
**Create controller.py. In this module add the following things:**

    - Define a class named Controller.
    - Build a constructor which calls model and view parameters in it.
    - Define 3 functions in it:
        1. calculateResult: for evaluating result of expression.
        2. buildExpression: for validating and building the expression.
        3. connectSignals: to connect the expression through the buttons we defined in Step-3.
