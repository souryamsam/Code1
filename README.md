Explanation of task 1
User Input
The program first asks the user to enter two numbers.
input() takes the values as strings, so int() converts them into integers.
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
Addition
It calculates the sum of a and b using the + operator.
print("addition =", a+b)
Subtraction
It subtracts the second number (b) from the first number (a) using the - operator.
print("subtraction =", a-b)
Multiplication
It multiplies the two numbers using the * operator.
print("multiplication =", a*b)
Division
It divides the first number (a) by the second number (b) using the / operator.
print("division =", a/b)
Note: Division always gives a float result in Python (e.g., 7 / 2 = 3.5).

Explanation of task 2
Input First Name
a = input("Enter the first name: ")
This asks the user to type their first name and stores it in the variable a.
Input Last Name
b = input("Enter the last name: ")
This asks the user to type their last name and stores it in the variable b.
Concatenate Strings
The print() statement combines text and the values of a and b:
"Hello, " + a + " " + b + "! Welcome to the Python program."
Here, the + operator is used to join strings.
(a space between a and b) ensures the first and last names don’t stick together.
