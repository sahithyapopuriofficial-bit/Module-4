# File Handling in Python: Count the number of words in the file

## 🎯 Aim
To write a Python program that count the number of words in a file.

## 🧠 Algorithm
1. Open the file `text_case_1.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - For each and every word in the file increment the count by 1.
4. After processing all lines, print the `count` value, which represents the number of words in the file.

## 🧾 Program
```
def create_file(file_path, file_content):
    with open(file_path,"w") as file:
        file.write(file_content)

def count_words_in_file(file_path):
    with open(file_path,"r") as file:
        content=file.read()
    words=content.split()
    return len(words)
        
```

## Output
<img width="1439" height="871" alt="image" src="https://github.com/user-attachments/assets/a7490205-05c8-46bd-a024-ca954ce65054" />

## Result
Thus,the given Python Program has been executed successfully.
