# calculate factorial using a function using loop
num=int(input("Enter a number: "))
fact=1
for i in range(num,0,-1):
    fact=fact*i
print(f"Factorial of {num} is: {fact}")

#calculate factorial using recursion
num=int(input("Enter a number: "))
def fact(num):
    if num==1 or num==0:
        return 1
    else:
        return num*fact(num-1)
print(f"Factorial of {num} is: {fact(num)}")
