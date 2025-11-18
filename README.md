# Python Lists — Examples & Basics

This repository contains simple and clear examples demonstrating how Python lists work.  
Useful for beginners learning Python fundamentals.

---

## 📌 Features Covered
- Creating lists  
- Indexing & slicing  
- Modifying lists  
- Looping through lists  
- Common list methods  
- Sorting & reversing  
- Nested lists  
- List comprehensions  

---

## 🚀 Example Code

```python
# code here
# your example list code

# Creating a list
fruits = ["apple", "banana", "cherry"]
print(fruits)

# Accessing elements
print(fruits[0])      # apple
print(fruits[-1])     # cherry

# Adding items
fruits.append("orange")
print(fruits)

# Removing items
fruits.remove("banana")
print(fruits)

# Looping
for item in fruits:
    print("Fruit:", item)

# List comprehension
numbers = [1, 2, 3, 4, 5]
squares = [n*n for n in numbers]
print(squares)
