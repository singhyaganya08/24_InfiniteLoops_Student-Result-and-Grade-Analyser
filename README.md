# 24_InfiniteLoops_Student-Result-and-Grade-Analyser

Batch: 24

Member 1: Shourya
Member 2: Yaganya Singh
Member 3: Shrayti Saraf

Objectives and Features:
•	Accept marks for five subjects for multiple students.
•	Calculate total marks, percentage, and grade.
•	Identify pass/fail status using a specified minimum mark in each subject.
•	Display the class topper and class average.

C Programming Concepts Used:
1. Variables and Data Types
2. Structures
3. Arrays
4. Strings
5. Functions
6. Loops
7. Conditional Statement
8. Switch Case
9. Operators
10. Input/Output
11. Input Validation
12. Nested Loops

Instructions to Compile and Execute the Program:
1. Save the C source code.
2. Open the file in a C compiler/IDE such as VS Code, Code::Blocks, Dev-C++, or GCC.
3.⁠ ⁠Compile the program to check for errors.
4. If using GCC, compile using: gcc student_grade_analyzer.c -o student_grade_analyzer
5. Run the compiled program: ./student_grade_analyzer
6. Enter the number of students when prompted.
7.⁠ ⁠Use the menu options to:
    * Enter student details and marks
    * Display student results
    * Display the class report
    * Exit the program

Expected Output: 
Student-wise result summary and class performance report including the name of topper along with their percentage.

Sample Output: 
===== STUDENT RESULT AND GRADE ANALYZER =====
Enter number of students (1-10): 2

===== MENU =====
1. Enter Student Details
2. Display Student Results
3. Display Class Report
4. Exit
Enter your choice: 1

Enter name of student 1: shrayti
Enter the marks for subject 1: 10
Enter the marks for subject 2: 20
Enter the marks for subject 3: 30
Enter the marks for subject 4: 40
Enter the marks for subject 5: 50

Enter name of student 2: abcd
Enter the marks for subject 1: 20
Enter the marks for subject 2: 30
Enter the marks for subject 3: 50
Enter the marks for subject 4: 30
Enter the marks for subject 5: 10

Student data entered successfully!

===== MENU =====
1. Enter Student Details
2. Display Student Results
3. Display Class Report
4. Exit
Enter your choice: 2

======STUDENT RESULT======

Name: shrayti
Total: 150.00 /500
Percentage: 30.00%
Grade: F
STATUS=FAIL

Name: abcd
Total: 140.00 /500
Percentage: 28.00%
Grade: F
STATUS=FAIL

===== MENU =====
1. Enter Student Details
2. Display Student Results
3. Display Class Report
4. Exit
Enter your choice: 3

=====CLASS REPORT=====
Topper: shrayti
Topper percentage: 30.00%
Class average: 29.00%

===== MENU =====
1. Enter Student Details
2. Display Student Results
3. Display Class Report
4. Exit
Enter your choice: 4

Exiting program..
