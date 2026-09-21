# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
nums = list(map(int, input("Enter elements separated by space: ").split()))

total = 0 for i in nums: total += i

print("Sum of elements:", total)
```

## Output
Enter elements separated by space: 1 2 3 4 5 Sum of elements: 15

## Result
The program executed successfully and calculated the sum of all elements in the list using a loop.
