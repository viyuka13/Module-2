## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
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

## 🧾 Program
      num = int(input())
      temp = num
      rev = 0
      while temp > 0:
          rev = (10 * rev) + temp % 10
          temp = temp // 10
      if rev == num:
          print("The number is a palindrome.")
      else:
          print("The number is not a palindrome.")
## Output
![image](https://github.com/user-attachments/assets/8537d5ef-886f-4405-9cc1-5be813c02095)

## Result
The Python program to check whether a given number is a palindrome has been executed successfully, and the output has been verified.

