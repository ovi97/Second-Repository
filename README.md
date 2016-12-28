# Second-Repository
print ("Options:")
print ("Enter 'Add' to add two numbers")
print ("Enter 'subtract' to subtracttwo numbers")
print ("Enter 'multiply' to multiply two numbers")
print ("Enter 'divide' to divide two numbers")
print ("Enter 'quit' to Quit")
user_input=(".")
if user_input=="quit":
print ("quitting")
elif user_input=="add":
num1=float (input("enter a number"))

num2=float (input ("enter another number"))


result=str(num1+num2)

print(result)
elif user_input=="subtract":
num1=float (input("enter a number"))

num2=float (input ("enter another number"))


result=str(num1-num2)

print(result)
elif user_input=="multiply":
num1=float (input("enter a number"))

num2=float (input ("enter another number"))


result=str(num1*num2)

print(result)
elif user_input=="divide":
num1=float (input("enter a number"))

num2=float (input ("enter another number"))


result=str(num1/num2)

print(result)
