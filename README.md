##                             README FILE OF PYTHON OPERATOR PRECEDENCE USING BODMAS METHOD


This document explains the precedence of operators in Python, following the BODMAS rule (Brackets, Orders,
Division/Multiplication, Addition/Subtraction), and including the modulus operator `%`.

## Understanding Operator Precedence

In Python, when you write an expression, the order in which operations are executed is determined by the precedence of the operators involved. 
This precedence dictates which operations are performed first when an expression contains multiple different operations. 

### The Order of Operations

1. **Brackets `()`**: Operations inside parentheses are performed first.
2. **Orders `**`**: Exponentiation (raising to a power) comes next.
3. **Division `/`, Multiplication `*`, and Modulus `%`**: These operations are on the same level and are performed from left to right.
4. **Addition `+` and Subtraction `-`**: Finally, addition and subtraction are performed from left to right.

### Detailed Examples

Let’s break down a few examples to see how Python handles these operations.

#### Example 1

'''python
result = 10 + 3 % 2 * 5 - 6 / 2


Step-by-step Evaluation:

Modulus %: 3 % 2 results in 1 (since the remainder of 3 divided by 2 is 1).
Multiplication * and Division /:
1 * 5 = 5
6 / 2 = 3
Addition + and Subtraction -:
10 + 5 = 15
15 - 3 = 12
Final Result: 12

python'''

## Example 2

result = (4 + 3) * 2 ** 2 / 2
Step-by-step Evaluation:

Brackets (): (4 + 3) results in 7.
Exponentiation **: 2 ** 2 = 4.
Multiplication * and Division /:
7 * 4 = 28
28 / 2 = 14
Final Result: 14

Example 3

result = 8 / 4 * 2 + 3 ** 2 % 5
Step-by-step Evaluation:

Exponentiation **: 3 ** 2 = 9.
Division / and Multiplication *:
8 / 4 = 2
2 * 2 = 4
Modulus %: 9 % 5 = 4 (remainder of 9 divided by 5).
Addition +: 4 + 4 = 8.
Final Result: 8

Example 4

result = 5 + 2 * (10 // 4) ** 3
Step-by-step Evaluation:

Brackets (): (10 // 4) results in 2 (integer division).
Exponentiation **: 2 ** 3 = 8.
Multiplication *: 2 * 8 = 16.
Addition +: 5 + 16 = 21.
Final Result: 21

Key Takeaways
Parentheses (): Always resolve expressions inside brackets first.
Exponentiation **: Next, evaluate any powers or roots.
Multiplication, Division, and Modulus: These operators are on the same level, evaluated left to right.
Addition and Subtraction: Finally, perform any addition or subtraction.
Understanding and applying these rules ensures that you can accurately predict the result of complex expressions in Python.









