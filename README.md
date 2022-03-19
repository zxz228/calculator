# calculator

import select
import numbers

def add(a,b):
 return a + b

def subtract(a,b):
 return a - b

def multiply(a,b):
 return a * b

def divide(a,b):
 return a / b


select = int(input("Введите операцию 1, 2, 3, 4 \n1-додать 2-віднять 3-помножить 4-поделить => "))

Number_1 = int(input("Введите 1 число"))
Number_2 = int(input("Введите 2 число"))

if select == 1:
 print(Number_1, "+", Number_2,"=",add(Number_1, Number_2))

elif select == 2:
 print(Number_1, "-", Number_2, "=", subtract(Number_1, Number_2))

elif select == 3:
 print(Number_1, "*", Number_2, "=", multiply(Number_1, Number_2))

elif select == 4:
    print(Number_1, "/", Number_2, "=",divide(Number_1, Number_2))

else:
     print("Введиное значение не правильное")
