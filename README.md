# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: VINOTH M P
RegisterNumber:  212223240182
*/

def newton_sqrt(num,num_iter=100):
    a=float(num)
    for i in range(num_iter):
        num=0.5*(num + a/num)
    return num
number = int(input())
sqrt_value = newton_sqrt(number)
print(f"Square root of the number: {sqrt_value}")

```

## Output:

![alt text](<Screenshot 2024-03-23 032354.png>)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
