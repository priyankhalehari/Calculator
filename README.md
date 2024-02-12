# Calculator
def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    return a/b
print("\nSelect operation")
print("\n1,addition\n2.subtraction\n3.multiplication\n4.division\n5.exit")
choice=int(input("Enter your choice:"))
if choice<=4:
  a=int(input("Enter first number:"))
  b=int(input("Enter second number:"))
else:
     print("Invalid choice")
if choice ==1:
     print("Sum=",add(a,b))
elif choice ==2:
     print("Difference=",sub(a,b))
elif choice ==3:
     print("Product=",mul(a,b))
elif choice ==4:
     print("Division=",div(a,b))
else:
     print("Exit")
