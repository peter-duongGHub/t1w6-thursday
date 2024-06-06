## Control Flow
Order in which lines of code are executed in a program.

<!-- print("Hello, welcome to programming with Python")

a = 10
b = 5
result = a + b

print("The result of adding {a} and {b} is {result}")

print("Thank you") -->

# Sequential control flow
Execution of code statements one after another, in the order they appear in the program

# Conditional control flow / Control flow
Execution of code statements based on some input

if tomorrow is Saturday
    set alarm for 7
if tomorrow is Tuesday
    set alarm for 6

# Boolean Data Type Re-visit 
Data type that has two values: True and False. Boolean values are used to control the flow of the program.

is_the_earth_flat = False
print(is_the_earth_flat)

i_am_happy = True
print(i_am_happy)



# Comparison Operators / Relational Operators
Decide the relationship between the operands. Result of comparison is a boolean value (True/False)

x = 5
y = 7
z = 9

print(y === z)


if tomorrow == Saturday:
    set alarm for 7
if tomorrow == Tuesday:
    set alarm for 6

# if, elif, else 
Simplest form of AI (you could say that)
'if' checks the condition, if true, the intended blocks get executed, if false, it skips the intended blocks

today = "Tuesday"

if today == "Monday":
    print("Set an alarm for 5 AM!")
elif today == "Tuesday":
    print("Set an alarm for 6 AM!")
elif today == "Saturday":
    print("Set an alarm for 7 AM!")


    temperature = 30

if temperature > 35:
    print("It's hot outside.")
elif temperature < 15:
    print("It's cold outside.")
else: 
    print("The weather is mild.")



# pass
Does not execute, just ..... passes.. for now

# Boolean Operators / Logical Operators
AND, OR, NOT. Operands needs to be boolean as well