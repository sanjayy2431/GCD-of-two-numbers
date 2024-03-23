# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Sanjay.V
RegisterNumber: 212223230188
*/
```
```
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```


## Output:
![Screenshot 2024-03-23 082758](https://github.com/sanjayy2431/GCD-of-two-numbers/assets/149365143/1be6c9b4-f7b0-4706-8f8e-65a70800549d)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
