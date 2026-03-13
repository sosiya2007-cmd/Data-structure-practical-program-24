# Reverse a string using stack

stack = []

string = input("Enter a string: ")

# Push characters into stack
for ch in string:
    stack.append(ch)

# Pop characters to reverse string
reverse = ""
while stack:
    reverse += stack.pop()

print("Reversed string:", reverse)# Data-structure-practical-program-24
