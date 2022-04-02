# For-While-Break-Continue-List-Comprehension-Errors-and-Exceptions-Handling

## For
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

This is less like the for keyword in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.

With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.

## While
A while loop statement in Python programming language repeatedly executes a target statement as long as a given condition is true. The syntax of a while loop in Python programming language is − Here, statement (s) may be a single statement or a block of statements. The condition may be any expression, and true is any non-zero value.

## Break
The break statement in Python terminates the current loop and resumes execution at the next statement. The most common use for break is when some external condition is triggered requiring a hasty exit from a loop.

## Continue
The continue statement in Python returns the control to the beginning of the while loop. The continue statement rejects all the remaining statements in the current iteration of the loop and moves the control back to the top of the loop. The continue statement can be used in both while and for loops

## Else After For
For is used to loop or interact up to the range limit that we have specified and for is also commonly used to loop through code that has known many iterations. else function to print the final result of the loop that we created, so if the result of the loop that we created has reached the end of the process, the else command will be executed.

## Pass
Pass is an instruction to python that no code is executed, so python continues executing the program below it. Lots of code blocks in python that we can't just leave empty. If we leave it blank the python interpreter will give an error. To work around this, we can put the pass statement as the body of the code block. That way the code block still doesn't do anything, but it doesn't cause an error either.

## List Comprehension
List comprehension is how to create a new list in a short way based on an existing list.
- List comprehension without ***if*** condition
- List comprehension with ***if*** condition
- List comprehension with *Nested Loops*

## Errors in Python
Python has two types of errors based on their occurrence
- **Syntax Errors:**
  Writing program syntax Errors (typo)
- **Logical Errors (Exceptions):**
  Programming process logic error

## Logical Errors (Exceptions) 
The exception handling process uses a try statement paired with except.
- **ZeroDivisionError:**
  An exception that occurs when program execution results in a mathematical calculation of division by zero.
- **FileNotFoundError:**
  An exception that occurs when the file to be open does not exist.
- **TypeError:**
  Unsupported operand type for mathematical calculation with different data types  
  
## Exceptions Handling
- **Handling ZeroDivisionError:**
  Using try and except ZeroDivisionError and print the error pop-up message to the screen.
- **Handling FileNotFoundError:**
  Using try, with ... as, except and print the pop-up error message to the screen.
- **Handling TypeError:**
  Using try, single or double except's statement and print the pop-up error message to the screen.
