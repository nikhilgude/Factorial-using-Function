# Factorial-using-Function
fact = 1
def factorial(n):
    global fact
    fact = 1
    for i in range(1, n+1):
        fact *=i
    return fact
num = int(input("eter the number"))
if num<0:
    print("cannot derive fact for _ve number")
else:
    factorial(num)
    print(f"factorial of {num} is",fact)
