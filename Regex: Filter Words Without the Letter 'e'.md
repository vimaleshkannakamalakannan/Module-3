# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
new_list=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      new_list.append(i)
print(new_list)
```
## Output
<img width="361" height="130" alt="image" src="https://github.com/user-attachments/assets/873ee4b1-943b-4c3e-98d3-fb5617fcf137" />

## Result
Thus,the program has been executed successfully.
