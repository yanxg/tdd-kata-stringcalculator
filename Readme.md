# String Calculator
https://osherove.com/tdd-kata-1/

## Before you start
- Try not to read ahead.
- Do one task at a time. The trick is to learn to work incrementally.
- Make sure you only test for correct inputs. there is no need to test for invalid inputs for this kata

## Task 1
Create a simple String calculator with a method signature:
```
int Add(string numbers)
```
The method can take up to two numbers, separated by commas, and will return their sum. 
for example “” or “1” or “1,2” as inputs.
(for an empty string it will return 0) 

### Hints
- Start with the simplest test case of an empty string and move to one and two numbers
- Remember to solve things as simply as possible so that you force yourself to write tests you did not think about
- Remember to refactor after each passing test

## Task 2
Allow the Add method to handle an unknown amount of numbers

## Task 3
Allow the Add method to handle new lines between numbers (instead of commas).
1. the following input is ok: “1\n2,3” (will equal 6)
2. the following input is NOT ok: “1,\n” (not need to prove it - just clarifying)