# PRODIGY_AndroidDevelopment_01
# Simple Calculator App
print("Simple Calculator")
print("Select operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")
# Take input from user
choice = input("Enter choice (1/2/3/4): ")
# Input numbers
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
# Perform operation
if choice == '1':
 print("Result:", num1 + num2)
elif choice == '2':
 print("Result:", num1 - num2)
elif choice == '3':
 print("Result:", num1 * num2)
elif choice == '4':
 if num2 != 0:
 print("Result:", num1 / num2)
 else:
 print("Error! Division by zero is not allowed.")
else:
 print("Invalid input")
