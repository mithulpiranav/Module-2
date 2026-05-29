
## NAME: MITHUL PIRANAV PD
## REGISTER NUMBER: 212224050019

# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## Aim:
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## Algorithm:
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## Program:
```
a=int(input())
z=bin(a)
print(z)
```

## Output:
<img width="949" height="254" alt="Screenshot 2026-02-04 113236" src="https://github.com/user-attachments/assets/20476afc-7300-4f87-bb54-18aaadde4ba2" />



## Result:
Thus, the python program was executed successfully.


# 2. Functions in Python: Modulo Calculator

## Aim:
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

##  Algorithm:
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

##  Program:
```
def result(a,b):
    return a%b
a=int(input())
b=int(input())
print(f"modulo is {result(a,b)}")
```

## Output:
<img width="971" height="278" alt="Screenshot 2026-02-04 113420" src="https://github.com/user-attachments/assets/b6f38136-1d41-415b-904b-e2d1b0fef4f7" />



## Result:
Thus, the python program was executed successfully.


# 3. Lambda Function in Python: Addition of Two Numbers

##  Aim:
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

##  Algorithm:
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

##  Program:
```
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```

## Output:

<img width="941" height="309" alt="Screenshot 2026-02-04 113535" src="https://github.com/user-attachments/assets/42a8ce02-39e4-41a7-8ec0-0e6203353be2" />



## Result:
Thus, the python program was executed successfully.



# 4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

##  Aim:

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

##  Algorithm:

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.


##  Program:
```
a=int(input())
for i in range(a):
    
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
```

## Output:
<img width="585" height="486" alt="Screenshot 2026-02-04 113659" src="https://github.com/user-attachments/assets/260985aa-2970-4f00-aa54-119509c01180" />




## Result:
Thus, the python program was executed successfully.


## 5. Loops in Python: Palindrome Number Checker

##  Aim:
To write a Python program that checks whether a given number is a **palindrome** using loops.

##  Algorithm:
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

##  Program:
```

num=int(input())
rev=0
temp=num

while temp>0:
    rem=temp%10
    rev=rev*10+rem
    temp//=10
    
if rev==num:
        print(f"The given number {num} is a Palindrome")
else:
        print(f"The given number {num} is not a palindrome")
```

## Output:
<img width="1024" height="238" alt="Screenshot 2026-02-04 113803" src="https://github.com/user-attachments/assets/30b4dbe5-ce4c-4396-b99d-56efc5821b5d" />



## Result:
Thus, the python program was executed successfully.
