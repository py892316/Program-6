# Program to find sum of the series: 1 - 2/2! + 3/3! - ... + n/n!

import math

n = int(input("Enter n: "))
s = 0

for i in range(1, n + 1):
    term = i / math.factorial(i)
    if i % 2 == 0:
        s -= term
    else:
        s += term

print("Sum of the series =", s)# Program-6
Python 
