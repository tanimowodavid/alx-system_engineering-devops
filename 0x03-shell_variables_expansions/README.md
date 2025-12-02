### [Task 0 (0-alisas)](/0x03-shell_variables_expansions/0-alias)

**Aim:**  
Create a script that creates an alias.

Name: `ls`  
Value: `rm \*`

---

### [Task 1 (1-hello_you)](/0x03-shell_variables_expansions/1-hello_you)

**Aim:**  
Create a script that prints hello user, where user is the current Linux user.

---

### [Task 2 (2-path)](/0x03-shell_variables_expansions/2-path)

**Aim:**  
Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.

---

### [Task 3 (3-paths)](/0x03-shell_variables_expansions/3-paths)

**Aim:**  
Create a script that counts the number of directories in the PATH.

---

### [Task 4 (4-global_variables)](/0x03-shell_variables_expansions/4-global_variables)

**Aim:**  
Create a script that lists environment variables.

---

### [Task 5 (5-local_variables)](/0x03-shell_variables_expansions/5-local_variables)

**Aim:**  
Create a script that lists all local variables and environment variables, and functions.

---

### [Task 6 (6-create_local_variable)](/0x03-shell_variables_expansions/6-create_local_variable)

**Aim:**  
Create a script that creates a new local variable.

Name: `BEST`  
Value: `School`

---

### [Task 7 (7-create_global_variable)](/0x03-shell_variables_expansions/7-create_global_variable)

**Aim:**  
Create a script that creates a new global variable.

Name: `BEST`  
Value: `School`

---

### [Task 8 (8-true_knowledge)](/0x03-shell_variables_expansions/8-true_knowledge)

**Aim:**  
Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

> `$(( ... ))` lets you do arithmetic expansion in bash

---

### [Task 9 (9-divide_and_rule)](/0x03-shell_variables_expansions/9-divide_and_rule)

**Aim:**  
Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.

> `POWER` and `DIVIDE` are environment variables

---

### [Task 10 (10-love_exponent_breath)](/0x03-shell_variables_expansions/10-love_exponent_breath)

**Aim:**  
Write a script that displays the result of `BREATH` to the power `LOVE`

> `BREATH` and `LOVE` are environment variables  
> The script should display the result, followed by a new line

---

### [Task 11 (11-binary_to_decimal)](/0x03-shell_variables_expansions/11-binary_to_decimal)

**Aim:**  
Write a script that converts a number from base 2 to base 10.

> The number in base 2 is stored in the environment variable BINARY  
> The script should display the number in base 10, followed by a new line

- use `base#number` to convert from a base to base 10

---

### [Task 12 (12-combinations)](/0x03-shell_variables_expansions/12-combinations)

**Aim:**  
Create a script that prints all possible combinations of two letters, except oo.

> - Letters are lower cases, from a to z
> - One combination per line
> - The output should be alpha ordered, starting with aa
> - Do not print oo
> - Your script file should contain maximum 64 characters

---

### [Task 13 (13-print_float)](/0x03-shell_variables_expansions/13-print_float)

**Aim:**  
Write a script that prints a number with two decimal places, followed by a new line.

> The number will be stored in the environment variable NUM.

---

### [Task 14 (100-decimal_to_hexadecimal)](/0x03-shell_variables_expansions/100-decimal_to_hexadecimal)

**Aim:**  
Write a script that converts a number from base 10 to base 16.

> - The number in base 10 is stored in the environment variable DECIMAL
> - The script should display the number in base 16, followed by a new line

---

### [Task 15 (101-rot13)](/0x03-shell_variables_expansions/101-rot13)

**Aim:**  
Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.  
**Explanation**

- `tr` (translate) replaces characters from one set with another.

- `'A-Za-z'` is the set of all uppercase and lowercase letters.

- `'N-ZA-Mn-za-m'` is the same letters shifted by 13 positions.

- ROT13 is symmetric, meaning:

  - applying it twice returns the original text.

- Input is taken from standard input.

---

### [Task 16 (102-odd)](/0x03-shell_variables_expansions/102-odd)

**Aim:**  
Write a script that prints every other line from the input, starting with the first line.

**Explanation**

- `awk` processes input line by line.

- `NR` is the current line number.

- `NR % 2 == 1` means:

      - print the line only if the line number is odd

  (1st, 3rd, 5th, …).

- Input comes from stdin, output goes to stdout.

---

### [Task 17 (103-water_and_stir)](/0x03-shell_variables_expansions/103-water_and_stir)

**Aim:**  
Write a shell script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.

> - WATER is in base water
> - STIR is in base stir.
> - The result should be in base bestchol

**Explanation**

- `32#$WATER` converts the variable `WATER` from base 32 → base 10.
- `STIR` is already a base-10 number, so no conversion needed.
- `$(( ... ))` performs arithmetic in bash.
- The result is printed in base 10 automatically.
- `echo` outputs the final value with a newline.

---
