# # Stack-Stack Reversal Program 🔁
NAME : G SANJAY
---
REG NO : 212224230243
---
This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
~~~
  stack = []
  n=int(input())
  for i in range(n):
     value=int(input())
     stack.append(value)
  reverse= []
  while stack:
     reverse.append(stack.pop())
  print(reverse)
~~~
## 🧪 Sample Input and Output
![image](https://github.com/user-attachments/assets/8758b301-bb6d-4036-bfc0-0017c6e357ed)

## Result
Thus, the program has been execueted successfully.
