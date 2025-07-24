Aim: To study and implement Operators in C++.

Tool: VS Code

Theory: In C++, operators are special symbols or keywords used to perform operations on variables and values. They are the foundation of most expressions and help manipulate data in various ways, such as arithmetic calculations, comparisons, logical evaluations, and more.

Arithmetic Operators: Arithmetic operators combined two or more numbers using a variety of mathematical techniques such as adding, subtracting, multiplying, etc. The basic number types for arithmetic operators are +,-,*,/,%. The arithmetic operators are often used in programming whenever calculations, evaluations, or iterative mathematics are required, such as financial computations, scientific simulations, or video games.

Relational Operators: Relational operators are used in programming to compare two objects or expressions to know their position. Relational operators will return one of two boolean values (true or false) based on the relationship of the two evaluated values. These are <,>,==,!=,=>,=<.Relational operators are one of the more important operators because they assist in program flow, via aspects of condition-based statements such as if, while or for statements. Relational operators can be used to ascertain equality, relationship such as ordering,when checking for specific criteria.

Program 1: Check if a Number is Positive, Negative, or Zero

Step-wise Algorithm

1. Start the program.


2. Declare an integer variable num.


3. Prompt the user: Enter a number.


4. Read input into num.


5. Check conditions:

If num > 0, print "Positive"

Else if num < 0, print "Negative"

Else, print "Zero"



6. End the program.




 Program 2: Calculate Average Marks and Display Grade

 Step-wise Algorithm

1. Start the program.


2. Declare five integer variables for subject marks:

mtt, nt, dcld, ss, edc



3. Prompt the user: Enter marks for MTT, NT, DCLD, SS, and EDC.


4. Read input values into the 5 subject variables.


5. Calculate total = mtt + nt + dcld + ss + edc


6. Compute average = total / 5


7. Check average validity:

If average < 0 or average > 100, print "Invalid input"



8. Check grade conditions:

If average > 90, print "O Grade"

Else if average >= 81, print "A+ Grade"

Else if average >= 71, print "A Grade"

Else if average >= 61, print "B Grade"

Else if average >= 51, print "C Grade"

Else, print "Fail"



9. End the program.




Program 3: Determine Coordinate Quadrant

 Step-wise Algorithm

1. Start the program.


2. Declare two integer/float variables x and y.


3. Prompt the user: Enter coordinates (x and y).


4. Read values into x and y.


5. Evaluate the position:

If x > 0 and y > 0, print "1st Quadrant"

Else if x < 0 and y > 0, print "2nd Quadrant"

Else if x < 0 and y < 0, print "3rd Quadrant"

Else if x > 0 and y < 0, print "4th Quadrant"

Else if x == 0 and y != 0, print "Y-axis"

Else if y == 0 and x != 0, print "X-axis"

Else, print "Origin"



6. End the program.

Conclusion: Hence, we used Logical Operators and Relational Operators and executed the decision-making statements to get an accurate output.
