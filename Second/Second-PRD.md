# Second PRD — Individual Java Challenge

## Submission Deadline

**August 5, 2026, before 6:00 PM**

Every student must complete the assigned requirement, push the complete project to GitHub, and share the repository URL with the Team Leader before **6:00 PM**.

The Team Leader must:

* Verify every team member’s repository.
* Update `report/report.txt`.
* Push the final team report before **6:00 PM**.
* Share the Team Leader’s repository URL with the trainer.

---

# Activity Objective

This activity is designed to evaluate the real Java understanding and individual programming ability of every student.

Every student must independently:

* Understand the assigned requirement.
* Select meaningful variables and data types.
* Create their own hard-coded values.
* Design the program logic.
* Write the complete Java program.
* Apply operators correctly.
* Use conditions and loops.
* Test the program with different hard-coded values.
* Fix errors.
* Capture the final output.
* Push the complete work to GitHub.
* Explain and modify the program when asked.

The activity is managed using teams, but every student will be evaluated individually.

---

# Concepts Covered

The requirements are based only on the topics completed so far.

## Java Fundamentals

* Introduction to Java
* Common Java applications
* Features of Java
* Java as a general-purpose language
* Roles of JDK, JRE and JVM
* Java execution flow
* Platform independence using bytecode
* First Java program
* Pseudocode and Java syntax
* Java program structure
* Output using `print` and `println`
* Primitive data types
* `String`
* Variables and naming rules
* Type conversion
* Type casting
* Integer division
* Decimal division
* String concatenation

## Operators

* Arithmetic operators
* Assignment operators
* Relational operators
* Logical operators
* Unary plus
* Unary minus
* Increment operator
* Decrement operator
* Operator precedence
* Ternary operator

## Control Flow

* Boolean expressions
* `if`
* `if-else`
* `else-if`
* Nested conditions
* Compound conditions
* `switch`

## Loops

* `while`
* `do-while`

---

# Important Programming Rule

## Hard-Coded Values Only

All programs must use only hard-coded values.

Students must declare and assign all required values directly inside the Java program.

Example:

```java
String studentName = "Aarav";
double academicPercentage = 72.5;
int attendancePercentage = 82;
boolean projectCompleted = true;
```

Students must not use runtime input.

The following are not allowed:

* `Scanner`
* `BufferedReader`
* Command-line arguments
* Keyboard input
* Console input
* File input
* Asking the user to enter values
* Any input method that receives values while the program is running

The following type of statement is not allowed:

```java
Scanner scanner = new Scanner(System.in);
```

---

# Hard-Coded Value Rules

Every student must:

1. Create their own variable names.
2. Create their own hard-coded values.
3. Avoid using the exact sample values shown in this document.
4. Use meaningful values related to the assigned problem.
5. Change the values and test the program multiple times.
6. Capture output for at least two different value sets.
7. Keep only one final value set in `sol/Main.java`.
8. Be ready to explain how the output changes when values are modified.

Students from the same team must not use identical:

* Variable names
* Values
* Output messages
* Conditions
* Project presentation format

---

# Individual Work Rule

Every student must complete the assigned requirement independently.

Students may discuss the meaning of Java concepts, but they must not:

* Share complete code.
* Copy another student’s program.
* Ask another person to write the program.
* Use identical variable names and values.
* Submit another student’s repository.
* Copy code from websites.
* Use generated code without understanding it.
* Submit code that they cannot explain.
* Use advanced concepts not covered in class without approval.

Every student must be able to explain and modify the complete program.

---

# AI Usage Rule

This activity is intended to evaluate real programming skills.

Students must not use AI tools to generate:

* Complete Java code
* Complete program logic
* Pseudocode
* Variable names
* Test values
* Output statements
* Requirement explanations
* Debugging solutions
* Project documentation

A working program alone does not guarantee marks.

Students may be asked to:

* Explain any statement.
* Explain the selected data type.
* Explain an operator.
* Explain the selected loop.
* Predict the output after changing values.
* Change a condition.
* Add one validation rule.
* Modify the program live.
* Correct an introduced error.
* Rewrite a part of the program without seeing the repository.

A student who cannot explain or modify the submitted program may lose marks and may be assigned for reassessment.

---

# Requirement Allocation Rules

The same list of 15 requirements applies to every team.

The Team Leader must follow these rules:

1. Every student must receive exactly one requirement.
2. No two students in the same team may receive the same requirement.
3. Requirements may repeat across different teams.
4. The Team Leader must allocate requirements before students start.
5. Students must not exchange requirements without approval.
6. The Team Leader must also complete one requirement individually.
7. Every student must use their own variable names.
8. Every student must use their own hard-coded values.
9. Every student must create an individual GitHub repository.
10. Every student must complete the activity before 6:00 PM.
11. The Team Leader must verify every repository.
12. The Team Leader must verify that no runtime input is used.
13. The Team Leader must update the final status honestly.

---

# Credit and Penalty Rules

| Submission Status                          | Credit Impact                    |
| ------------------------------------------ | -------------------------------- |
| Completed correctly before 6:00 PM         | Full credits                     |
| Completed with minor issues before 6:00 PM | Partial credits                  |
| Submitted after 6:00 PM                    | Credit deduction                 |
| Partially completed                        | Major credit deduction           |
| Required files missing                     | Credit deduction                 |
| Runtime input used                         | Requirement violation            |
| Program not working                        | Credit deduction                 |
| Unable to explain the program              | Verification failure             |
| Not submitted                              | Zero credits                     |
| Copied submission                          | Negative points and reassessment |
| False completion status                    | Negative points                  |
| Repository inaccessible                    | Treated as not submitted         |
| AI-generated work without understanding    | Negative points and reassessment |

Students who do not complete the activity will lose the available activity credits.

Copied work, false reporting, or inability to explain the submitted program may result in negative points.

---

# Common Mandatory Requirements

Every submission must:

* Use a valid Java program structure.
* Use only hard-coded values.
* Use meaningful variable names.
* Use suitable primitive data types and `String`.
* Use student-created values.
* Use at least one arithmetic operator.
* Use at least one assignment operator.
* Use at least one relational operator.
* Use at least one logical operator.
* Use at least one Boolean expression.
* Use at least one condition.
* Use either a `while` loop or a `do-while` loop.
* Use type casting when decimal accuracy is required.
* Handle integer and decimal division correctly.
* Use unary operators where required.
* Use the ternary operator where required.
* Handle invalid or unrealistic values using conditions.
* Produce meaningful output.
* Test the program with different hard-coded values.
* Upload final output screenshots.
* Be ready for live explanation and modification.

---

# Individual Java Practice Requirements

## Important Note

The sample values and sample outputs are provided only to explain the expected behaviour.

Students must not copy the exact sample values.

Students must create their own:

* Names
* Numbers
* Boolean values
* Scores
* Percentages
* Messages
* Variable names

No solution code or pseudocode is provided.

---

# Requirement 1 — Placement Readiness Evaluator

## Problem Statement

Create a Java program that evaluates whether a student is ready to attend a placement drive.

## Hard-Coded Details

Declare values for:

* Student name
* Academic percentage
* Attendance percentage
* Active backlogs
* Project completion status
* Communication score
* Aptitude score

## Eligibility Rules

A student is placement-ready only when:

* Academic percentage is at least `60`
* Attendance percentage is at least `75`
* Active backlogs are `0`
* Project is completed
* Communication score is at least `60`
* Aptitude score is at least `60`

## Program Requirements

Display:

* Student name
* Academic status
* Attendance status
* Backlog status
* Project status
* Communication status
* Aptitude status
* Final placement-readiness result
* Areas that require improvement

Use a loop to evaluate at least two different student profiles by changing or resetting hard-coded values inside the program.

## Mandatory Concepts

* Primitive data types
* `String`
* Boolean values
* Relational operators
* Logical operators
* Compound conditions
* Nested conditions
* Ternary operator
* `while` or `do-while`

## Sample Values

```text
Student Name: Ananya
Academic Percentage: 72.5
Attendance Percentage: 81
Active Backlogs: 0
Project Completed: true
Communication Score: 68
Aptitude Score: 74
```

## Sample Output

```text
PLACEMENT READINESS REPORT

Student Name: Ananya
Academic Status: Eligible
Attendance Status: Eligible
Backlog Status: Eligible
Project Status: Completed
Communication Status: Eligible
Aptitude Status: Eligible

Final Result: PLACEMENT READY
Message: All placement requirements are satisfied.
```

## Another Possible Output

```text
Student Name: Kiran
Academic Status: Eligible
Attendance Status: Not Eligible
Backlog Status: Eligible
Project Status: Not Completed
Communication Status: Eligible
Aptitude Status: Needs Improvement

Final Result: NOT PLACEMENT READY

Areas to Improve:
Attendance
Project Completion
Aptitude Score
```

---

# Requirement 2 — Weekly Coding Practice Tracker

## Problem Statement

Create a Java program that tracks coding practice for seven days.

## Hard-Coded Details for Each Day

Create values for:

* Problems attempted
* Problems solved
* Practice hours

Since arrays have not been covered, process each day using variables and a `while` loop.

Students may update the values based on the current loop day using conditions.

## Rules

A day is productive when:

* At least `5` problems are solved
* Practice time is at least `2` hours

The weekly target is `35` solved problems.

## Program Requirements

Display:

* Total problems attempted
* Total problems solved
* Total practice hours
* Success percentage
* Average problems solved
* Productive days
* Non-productive days
* Weekly target status
* Final consistency message

Avoid division by zero.

## Mandatory Concepts

* Arithmetic operators
* Assignment operators
* Increment operator
* Type casting
* Decimal division
* Relational operators
* Logical operators
* `while`
* Ternary operator

## Sample Output

```text
WEEKLY CODING PRACTICE REPORT

Total Problems Attempted: 50
Total Problems Solved: 37
Success Percentage: 74.0%
Total Practice Hours: 15.5
Average Problems Solved Per Day: 5.28

Productive Days: 6
Non-Productive Days: 1

Weekly Target: Achieved
Consistency Status: Good
```

---

# Requirement 3 — Mock Test Attempt Manager

## Problem Statement

Create a Java program that manages a student’s mock-test attempts.

## Hard-Coded Details

Create values for three attempts:

* Score
* Correct answers
* Incorrect answers

## Rules

* Passing score is `60`
* Maximum attempts are `3`
* Stop evaluating when the student passes
* Track the best score
* Display remaining attempts

## Program Requirements

Display:

* Attempt number
* Score
* Correct answers
* Incorrect answers
* Pass or fail status
* Best score
* Remaining attempts
* Final result
* Recommendation

## Mandatory Concepts

* `while` or `do-while`
* Increment operator
* Decrement operator
* Assignment operators
* Relational operators
* Logical operators
* Nested conditions
* Ternary operator

## Sample Output

```text
MOCK TEST ATTEMPT REPORT

Attempt 1
Score: 48
Result: Failed
Remaining Attempts: 2

Attempt 2
Score: 57
Result: Failed
Remaining Attempts: 1

Attempt 3
Score: 68
Result: Passed

Best Score: 68
Final Result: MOCK TEST CLEARED
Message: Student passed on attempt 3.
```

---

# Requirement 4 — Personal Expense and Savings Analyser

## Problem Statement

Create a Java program that analyses monthly income, expenses, and savings.

## Hard-Coded Details

Declare values for:

* Monthly income
* Home contribution
* Rent
* Food expenses
* Travel expenses
* Education expenses
* Other expenses

## Program Requirements

Calculate and display:

* Total expenses
* Remaining amount
* Savings percentage
* Expense percentage
* Whether expenses exceed income
* Financial category
* Improvement message

## Suggested Categories

* Savings below 10%: Critical
* 10% to below 20%: Needs Improvement
* 20% to below 30%: Good
* 30% and above: Excellent

Use a loop to analyse at least two monthly scenarios.

## Mandatory Concepts

* Arithmetic operators
* Assignment operators
* Relational operators
* Logical operators
* Type casting
* Decimal division
* `if-else-if`
* Ternary operator
* `do-while`

## Sample Output

```text
MONTHLY FINANCIAL REPORT

Monthly Income: 70000.0
Total Expenses: 50000.0
Savings: 20000.0

Expense Percentage: 71.43%
Savings Percentage: 28.57%

Financial Category: Good
Message: Savings are healthy but can be improved.
```

---

# Requirement 5 — Student Marks and Grade Report

## Problem Statement

Create a Java program that evaluates marks for five subjects.

## Hard-Coded Details

Declare:

* Student name
* Five subject marks

## Rules

* Marks must be between `0` and `100`
* Passing mark is `35`
* The student fails if any subject mark is below `35`

## Grade Rules

* 90 and above: A+
* 80 to below 90: A
* 70 to below 80: B
* 60 to below 70: C
* 50 to below 60: D
* Below 50: Needs Improvement

## Program Requirements

Display:

* Total marks
* Average
* Percentage
* Passed-subject count
* Failed-subject count
* Pass or fail
* Grade
* Next-level eligibility
* Final message

Use a loop to process the five subjects using hard-coded values selected based on the loop count.

## Mandatory Concepts

* `while`
* Arithmetic operators
* Assignment operators
* Relational operators
* Logical operators
* Type casting
* Nested conditions
* Ternary operator

## Sample Output

```text
STUDENT MARKS REPORT

Student Name: Rahul
Total Marks: 370
Average Marks: 74.0
Percentage: 74.0%

Passed Subjects: 5
Failed Subjects: 0

Overall Result: PASS
Grade: B
Next-Level Eligibility: Eligible
```

---

# Requirement 6 — Attendance and Consistency Tracker

## Problem Statement

Create a Java program that tracks attendance for ten working days.

## Hard-Coded Attendance Values

Use:

* `1` for present
* `0` for absent

Declare or assign one value for each day.

## Rules

* Minimum attendance is `75%`
* Any value other than `0` or `1` is invalid
* Invalid values must not be counted

## Program Requirements

Display:

* Total working days
* Present days
* Absent days
* Attendance percentage
* Eligibility status
* Invalid attendance entries
* Final consistency message

## Mandatory Concepts

* Increment operator
* Assignment operators
* Arithmetic operators
* Type casting
* Decimal division
* Relational operators
* Logical operators
* `while`
* Ternary operator

## Sample Output

```text
ATTENDANCE REPORT

Total Working Days: 10
Present Days: 8
Absent Days: 2
Attendance Percentage: 80.0%

Required Attendance: 75.0%
Eligibility Status: ELIGIBLE
Consistency Status: Good Attendance
```

---

# Requirement 7 — Menu-Based Operator Explorer

## Problem Statement

Create a menu-driven Java program that performs operations on two hard-coded numbers.

## Hard-Coded Values

Declare:

* First number
* Second number
* A sequence of menu choices

Since runtime input is not allowed, menu choices must also be hard-coded.

Example concept:

```text
First operation choice: Addition
Second operation choice: Increment
Third operation choice: Comparison
Final operation choice: Exit
```

Students must create their own numeric menu-choice values.

## Menu Options

```text
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Remainder
6. Increment First Number
7. Decrement Second Number
8. Compare Numbers
9. Change Sign
10. Exit
```

## Program Requirements

The program must:

* Display the selected operation
* Perform multiple operations using a loop
* Update values after increment, decrement, or sign change
* Handle division by zero
* Handle an invalid hard-coded menu choice
* Stop when the exit choice is reached

## Mandatory Concepts

* `switch`
* `do-while`
* Arithmetic operators
* Assignment operators
* Relational operators
* Unary plus
* Unary minus
* Increment
* Decrement
* Ternary operator

## Sample Output

```text
Initial First Number: 12
Initial Second Number: 5

Selected Operation: Addition
Result: 17

Selected Operation: Increment First Number
Updated First Number: 13

Selected Operation: Compare Numbers
Result: First number is greater.

Selected Operation: Change Sign
Updated First Number: -13

Selected Operation: Exit
Operator Explorer Closed.
```

---

# Requirement 8 — Interview Preparation Progress Checker

## Problem Statement

Create a Java program that evaluates interview preparation.

## Hard-Coded Details

Declare:

* Student name
* Programming score
* Aptitude score
* Communication score
* Resume completion status
* Mock interview completion status
* Project completion status

## Suggested Rules

A student is interview-ready when:

* Programming score is at least `65`
* Aptitude score is at least `60`
* Communication score is at least `60`
* Resume is completed
* Mock interview is completed
* Project is completed

## Program Requirements

Display:

* Programming status
* Aptitude status
* Communication status
* Resume status
* Mock-interview status
* Project status
* Overall preparation percentage
* Final readiness result
* Weak areas
* Recommended action

## Mandatory Concepts

* Arithmetic operators
* Type casting
* Relational operators
* Logical operators
* Compound conditions
* Nested conditions
* Ternary operator
* `while` or `do-while`

## Sample Output

```text
INTERVIEW PREPARATION REPORT

Student Name: Naveen
Programming Status: Ready
Aptitude Status: Ready
Communication Status: Ready
Resume Status: Completed
Mock Interview Status: Completed
Project Status: Completed

Overall Preparation Percentage: 78.53%
Final Result: INTERVIEW READY
Recommended Action: Start applying and continue mock practice.
```

---

# Requirement 9 — Login Attempt and Account Security Simulator

## Problem Statement

Create a Java program that simulates repeated login attempts using hard-coded credentials.

## Hard-Coded Details

Declare:

* Correct username
* Correct PIN
* Username used in attempt 1
* PIN used in attempt 1
* Username used in attempt 2
* PIN used in attempt 2
* Username used in attempt 3
* PIN used in attempt 3

## Rules

* Maximum attempts are `3`
* Both username and PIN must be correct
* Stop when login is successful
* Lock the account after three failed attempts
* Display remaining attempts

## Program Requirements

Display:

* Attempt number
* Username status
* PIN status
* Login success or failure
* Remaining attempts
* Account-lock status
* Final message

## Mandatory Concepts

* `while` or `do-while`
* `String`
* Relational operators
* Logical operators
* Increment or decrement operator
* Nested conditions
* Ternary operator

## Sample Output

```text
LOGIN SECURITY REPORT

Attempt 1
Username Status: Correct
PIN Status: Incorrect
Login Result: Failed
Remaining Attempts: 2

Attempt 2
Username Status: Correct
PIN Status: Correct
Login Result: Successful

Welcome, learner01.
```

---

# Requirement 10 — Health and Fitness Status Calculator

## Problem Statement

Create a Java program that evaluates basic health and fitness information.

## Hard-Coded Details

Declare:

* Person name
* Height in metres
* Weight in kilograms
* Age
* Daily activity hours
* Water intake
* Sleep hours

## BMI Formula

```text
BMI = Weight / (Height × Height)
```

## BMI Categories

* Below 18.5: Underweight
* 18.5 to below 25: Normal
* 25 to below 30: Overweight
* 30 and above: Obese

## Health Rules

* Daily activity of at least 1 hour is good
* Water intake of at least 2 litres is good
* Sleep between 7 and 9 hours is healthy

## Program Requirements

Display:

* BMI value
* BMI category
* Activity status
* Water-intake status
* Sleep status
* Overall fitness category
* Improvement message

Use a loop to evaluate at least two profiles.

## Mandatory Concepts

* Arithmetic operators
* Type casting
* Decimal division
* Relational operators
* Logical operators
* `if-else-if`
* Ternary operator
* `while` or `do-while`

## Sample Output

```text
HEALTH AND FITNESS REPORT

Name: Meera
BMI: 22.04
BMI Category: Normal

Activity Status: Good
Water Intake Status: Good
Sleep Status: Healthy

Overall Fitness Status: HEALTHY
Message: Continue maintaining the same routine.
```

---

# Requirement 11 — Daily Study Hours Evaluator

## Problem Statement

Create a Java program that evaluates study hours for seven days.

## Hard-Coded Details

Declare study hours for seven days.

## Rules

* Daily target is `3` hours
* A successful day is a day where study hours are at least `3`

## Consistency Categories

* 6 or 7 successful days: Excellent
* 4 or 5 successful days: Good
* 2 or 3 successful days: Developing
* Fewer than 2 successful days: Needs Improvement

## Program Requirements

Display:

* Total study hours
* Average study hours
* Days meeting the target
* Days below the target
* Highest study-hours value
* Overall consistency status
* Final improvement message

## Mandatory Concepts

* `while`
* Arithmetic operators
* Assignment operators
* Increment operator
* Type casting
* Decimal division
* Relational operators
* Logical operators
* Ternary operator

## Sample Output

```text
WEEKLY STUDY REPORT

Total Study Hours: 21.0
Average Study Hours: 3.0
Highest Study Hours: 4.0

Days Meeting Target: 5
Days Below Target: 2

Consistency Status: Good
Message: Improve the low-study days and maintain consistency.
```

---

# Requirement 12 — Product Purchase and Discount Calculator

## Problem Statement

Create a Java program that calculates the final amount for a product purchase.

## Hard-Coded Details

Declare:

* Product name
* Product price
* Quantity
* Customer category
* Membership status
* Tax percentage
* Delivery charge

## Customer Categories

```text
1. Regular Customer
2. Student Customer
3. Premium Customer
```

## Suggested Discount Rules

* Regular: 5%
* Student: 10%
* Premium: 15%
* Additional membership discount: 5%

Students may modify the discount values.

## Program Requirements

Calculate and display:

* Original amount
* Customer discount
* Membership discount
* Amount after discount
* Tax amount
* Delivery charge
* Final payable amount
* Benefit status

Use a hard-coded customer category and a `switch` statement.

## Mandatory Concepts

* Arithmetic operators
* Assignment operators
* Type casting
* Decimal division
* Relational operators
* Logical operators
* Nested conditions
* `switch`
* Ternary operator

## Sample Output

```text
PURCHASE BILL

Product: Headphones
Original Amount: 5000.0
Customer Discount: 500.0
Membership Discount: 250.0
Amount After Discount: 4250.0
Tax Amount: 765.0
Delivery Charge: 100.0

Final Payable Amount: 5115.0
Benefit Status: Membership benefit applied.
```

---

# Requirement 13 — Number Behaviour Analyser

## Problem Statement

Create a repeating menu-driven Java program that analyses and modifies one hard-coded number.

## Hard-Coded Details

Declare:

* Starting number
* A sequence of menu choices
* Comparison number
* Divisibility-check number

## Menu

```text
1. Check Positive, Negative or Zero
2. Check Even or Odd
3. Check Divisibility
4. Compare with Another Number
5. Increment the Number
6. Decrement the Number
7. Change the Sign
8. Display Current Value
9. Exit
```

## Program Requirements

The program must:

* Perform multiple hard-coded menu operations
* Use `switch`
* Update the number when modified
* Handle invalid choices
* Stop when Exit is reached

## Mandatory Concepts

* `switch`
* `do-while`
* Modulus operator
* Relational operators
* Logical operators
* Unary minus
* Increment
* Decrement
* Ternary operator

## Sample Output

```text
Starting Number: 12

Selected Operation: Positive, Negative or Zero
Result: Positive Number

Selected Operation: Even or Odd
Result: Even Number

Selected Operation: Divisibility
Result: 12 is divisible by 3

Selected Operation: Increment
Updated Number: 13

Selected Operation: Change Sign
Updated Number: -13

Selected Operation: Display Current Value
Current Number: -13

Selected Operation: Exit
Number Analyser Closed.
```

---

# Requirement 14 — Course Selection Adviser

## Problem Statement

Create a Java program that recommends a learning path based on a student’s interest and readiness.

## Hard-Coded Details

Declare:

* Student name
* Interest category
* Programming confidence
* Logical ability
* Daily study time
* Career goal
* Current preparation level

## Interest Categories

```text
1. Software Development
2. Data and Analytics
3. Testing
4. Web Development
```

## Program Requirements

Use a hard-coded interest-category number and display:

* Selected interest
* Readiness status
* Recommended learning path
* Suggested study target
* Whether foundation revision is required
* Final recommendation

The program must not recommend an advanced path when scores are low.

## Mandatory Concepts

* `switch`
* `if-else`
* Nested conditions
* Relational operators
* Logical operators
* Compound conditions
* Ternary operator
* `while` or `do-while`

## Sample Output

```text
COURSE SELECTION REPORT

Student Name: Naveen
Selected Interest: Software Development
Career Goal: Backend Developer

Readiness Status: Ready to Begin
Recommended Learning Path: Programming Fundamentals and Java Development
Suggested Daily Study Time: 3 Hours
Foundation Revision Required: No

Final Recommendation:
Begin the learning path and practise consistently.
```

---

# Requirement 15 — Learning Streak and Productivity Tracker

## Problem Statement

Create a Java program that evaluates a student’s learning performance for seven days.

## Hard-Coded Details for Each Day

Declare values for:

* Learning activity completed
* Practice activity completed
* Homework completed
* Problems solved
* Study hours

## Completion Rules

A day is fully completed when:

* Learning is completed
* Practice is completed
* Homework is completed

A day is partially completed when at least one activity is completed.

A day is missed when no activity is completed.

A productive day requires:

* At least `5` problems solved
* At least `2` study hours

## Program Requirements

Display:

* Fully completed days
* Partially completed days
* Missed days
* Productive days
* Total problems solved
* Total study hours
* Average study hours
* Completion percentage
* Longest successful streak
* Final consistency category
* Motivation message

## Mandatory Concepts

* `while`
* Boolean expressions
* Arithmetic operators
* Assignment operators
* Relational operators
* Logical operators
* Increment operator
* Type casting
* Decimal division
* Nested conditions
* Ternary operator

## Sample Output

```text
WEEKLY LEARNING PRODUCTIVITY REPORT

Fully Completed Days: 4
Partially Completed Days: 2
Missed Days: 1
Productive Days: 4

Total Problems Solved: 33
Total Study Hours: 14.0
Average Study Hours: 2.0
Completion Percentage: 57.14%

Longest Successful Streak: 2 Days

Consistency Category: Good
Motivation Message:
Reduce missed days and continue building consistency.
```

---

# Repository Name

Every student, including the Team Leader, must create a repository named exactly:

```text
Second-PRD
```

---

# Team Member Repository Structure

Every team member must follow this structure:

```text
Second-PRD/
│
├── Project-Title/
│   ├── requirement/
│   │   └── requirement.md
│   ├── src/
│   │   └── Main.java
│   ├── sol/
│   │   └── Main.java
│   └── design-output/
│       ├── output-1.png
│       └── output-2.png
│
└── README.md
```

## Example

```text
Second-PRD/
│
├── Weekly-Coding-Practice-Tracker/
│   ├── requirement/
│   │   └── requirement.md
│   ├── src/
│   │   └── Main.java
│   ├── sol/
│   │   └── Main.java
│   └── design-output/
│       ├── output-1.png
│       └── output-2.png
│
└── README.md
```

---

# Team Leader Repository Structure

The Team Leader must complete an individual project and maintain the team report.

```text
Second-PRD/
│
├── Project-Title/
│   ├── requirement/
│   │   └── requirement.md
│   ├── src/
│   │   └── Main.java
│   ├── sol/
│   │   └── Main.java
│   └── design-output/
│       ├── output-1.png
│       └── output-2.png
│
├── report/
│   └── report.txt
│
└── README.md
```

Only the Team Leader must create the `report` folder.

---

# Project Title Folder

The folder name must match the assigned project title.

Use hyphens between words.

Example:

```text
Placement-Readiness-Evaluator
```

Do not use spaces or unnecessary special characters.

---

# `requirement/requirement.md`

This file must contain:

```text
Student Name:
Email:
Team Number:
GitHub Username:
Assigned Requirement Number:
Project Title:
```

The student must also write:

* Understanding of the requirement
* Hard-coded values selected
* Variables and data types planned
* Outputs expected
* Arithmetic operators planned
* Assignment operators planned
* Relational operators planned
* Logical operators planned
* Unary operators planned
* Ternary operator usage
* Conditions required
* Loop selected
* Reason for selecting the loop
* Validation rules
* Test value sets planned

This content must be written in the student’s own words.

No Java code must be written inside this file.

---

# `src/Main.java`

The `src` folder must contain the development version.

```text
src/
└── Main.java
```

Students must write and improve the program in this file.

The program must use:

* Hard-coded values only
* Student-created variable names
* Student-created values
* Meaningful output messages
* Concepts completed in class
* Independent logic

---

# `sol/Main.java`

The `sol` folder must contain the final completed and tested program.

```text
sol/
└── Main.java
```

The final program must:

* Compile successfully
* Run successfully
* Meet the assigned requirement
* Use only hard-coded values
* Contain the corrected version
* Match the uploaded output
* Be explainable by the student

Students must first develop the program in:

```text
src/Main.java
```

After testing, the final version must be copied to:

```text
sol/Main.java
```

---

# `design-output`

The `design-output` folder must contain output screenshots.

Students must test at least two different hard-coded value sets.

Required structure:

```text
design-output/
├── output-1.png
└── output-2.png
```

The student must:

1. Run the program using the first value set.
2. Capture the output.
3. Change the hard-coded values.
4. Run the program again.
5. Capture the second output.
6. Restore the final selected values in `sol/Main.java`.

The screenshots must match the program behaviour.

---

# Root `README.md`

Every student must update the root `README.md`.

Use this format:

```text
Student Name:
Email:
Team Number:
GitHub Username:
Requirement Number:
Project Title:
Repository URL:
Submission Time:
Submission Status:
```

The student must also mention:

* What the project does
* Hard-coded values used
* Java concepts used
* Data types used
* Arithmetic operators used
* Assignment operators used
* Relational operators used
* Logical operators used
* Unary operators used
* Ternary operator usage
* Conditions used
* Loop used
* Number of value sets tested
* Whether the program works
* Whether output screenshots are uploaded
* One difficulty faced
* One error corrected
* One learning from the activity

---

# Team Leader `report.txt`

Only the Team Leader must maintain:

```text
report/report.txt
```

The file name must be exactly:

```text
report.txt
```

## Required Format

```text
TEAM NUMBER:

TEAM LEADER NAME:

TOTAL TEAM MEMBERS:

SUBMISSION DEADLINE: AUGUST 5, 2026 — 6:00 PM

============================================================

SL. NO.:
NAME:
EMAIL:
REPOSITORY URL:
ASSIGNED REQUIREMENT NUMBER:
PROJECT TITLE:
REQUIRED FILES STATUS:
HARD-CODED VALUES STATUS:
RUNTIME INPUT STATUS:
PROGRAM STATUS:
OUTPUT STATUS:
EXPLANATION STATUS:
SUBMISSION TIME:
FINAL STATUS:

============================================================
```

Repeat the same section for every team member.

---

# Sample `report.txt`

```text
TEAM NUMBER: 01

TEAM LEADER NAME: Student Name

TOTAL TEAM MEMBERS: 11

SUBMISSION DEADLINE: AUGUST 5, 2026 — 6:00 PM

============================================================

SL. NO.: 1
NAME: Student One
EMAIL: studentone@email.com
REPOSITORY URL: https://github.com/username/Second-PRD
ASSIGNED REQUIREMENT NUMBER: 2
PROJECT TITLE: Weekly Coding Practice Tracker
REQUIRED FILES STATUS: COMPLETE
HARD-CODED VALUES STATUS: VERIFIED
RUNTIME INPUT STATUS: NOT USED
PROGRAM STATUS: WORKING
OUTPUT STATUS: UPLOADED
EXPLANATION STATUS: EXPLAINED
SUBMISSION TIME: 5:20 PM
FINAL STATUS: COMPLETED

============================================================

SL. NO.: 2
NAME: Student Two
EMAIL: studenttwo@email.com
REPOSITORY URL: https://github.com/username/Second-PRD
ASSIGNED REQUIREMENT NUMBER: 6
PROJECT TITLE: Attendance and Consistency Tracker
REQUIRED FILES STATUS: INCOMPLETE
HARD-CODED VALUES STATUS: VERIFIED
RUNTIME INPUT STATUS: NOT USED
PROGRAM STATUS: NOT WORKING
OUTPUT STATUS: MISSING
EXPLANATION STATUS: NOT VERIFIED
SUBMISSION TIME: 5:50 PM
FINAL STATUS: PARTIALLY COMPLETED

============================================================
```

---

# Allowed Final Status Values

The Team Leader must use only one of these statuses:

```text
COMPLETED
PARTIALLY COMPLETED
NOT COMPLETED
NOT SUBMITTED
SUBMITTED LATE
REPOSITORY NOT ACCESSIBLE
REQUIREMENT FILE MISSING
SRC MISSING
SOLUTION MISSING
OUTPUT MISSING
PROGRAM NOT WORKING
RUNTIME INPUT USED
HARD-CODED VALUES NOT USED
EXPLANATION NOT VERIFIED
VERIFICATION REQUIRED
COPIED SUBMISSION SUSPECTED
ABSENT
```

---

# Team Leader Responsibilities

The Team Leader must:

1. Prepare the complete team-member list.
2. Assign one unique requirement to every member.
3. Ensure no requirement repeats within the team.
4. Complete one requirement individually.
5. Ensure every student uses hard-coded values only.
6. Ensure no student uses `Scanner`.
7. Ensure no student uses runtime input.
8. Collect every repository URL.
9. Open every repository.
10. Verify the project-title folder.
11. Verify `requirement/requirement.md`.
12. Verify `src/Main.java`.
13. Verify `sol/Main.java`.
14. Verify both output screenshots.
15. Check whether the program works.
16. Ask every student to explain at least one part.
17. Change one hard-coded value and ask the student to predict the output.
18. Record the submission time.
19. Update the correct status.
20. Identify missing and incomplete submissions.
21. Push `report/report.txt` before 6:00 PM.
22. Share only the Team Leader repository URL with the trainer.

The Team Leader must not:

* Write another student’s program.
* Modify another student’s repository.
* Copy student programs.
* Mark incomplete work as completed.
* Give the same requirement to two members.
* Mark runtime-input programs as completed.
* Hide missing or copied submissions.
* Provide false completion information.

False reporting may result in negative points for the Team Leader.

---

# Team Member Responsibilities

Every team member must:

1. Receive one requirement from the Team Leader.
2. Create a repository named `Second-PRD`.
3. Create the assigned project-title folder.
4. Create `requirement/requirement.md`.
5. Write the development program in `src/Main.java`.
6. Use hard-coded values only.
7. Avoid `Scanner` and all runtime input.
8. Add the final program to `sol/Main.java`.
9. Test at least two different value sets.
10. Upload two output screenshots.
11. Update the root `README.md`.
12. Use their own variable names.
13. Use their own values.
14. Complete the logic independently.
15. Ensure the repository is accessible.
16. Push the complete repository before 6:00 PM.
17. Share the repository URL with the Team Leader.
18. Be ready to explain and modify the program.

Team members must not create the `report` folder.

---

# Git Commit Expectations

Students should use meaningful commits.

Recommended commits:

```text
Created project structure
Added requirement understanding
Added hard-coded variables and data types
Implemented calculations and operators
Added conditions and decision-making
Added while or do-while loop
Tested first value set
Tested second value set
Fixed program errors
Added final solution and outputs
Updated README
```

Avoid meaningless commit messages such as:

```text
update
changes
done
final
code
modified
```

A repository containing only one final commit may require additional verification.

---

# Individual Evaluation Criteria

| Evaluation Area                     |   Marks |
| ----------------------------------- | ------: |
| Requirement understanding           |      10 |
| Program structure and variables     |      10 |
| Correct use of hard-coded values    |      10 |
| Arithmetic and assignment operators |      10 |
| Relational and logical operators    |      10 |
| Unary and ternary operators         |      10 |
| Conditions and decision-making      |      10 |
| Loop implementation                 |      10 |
| Testing with multiple value sets    |      10 |
| Explanation and live modification   |      10 |
| **Total**                           | **100** |

---

# Live Verification

Students may be asked to:

* Explain the Java execution flow.
* Explain JDK, JRE and JVM.
* Explain platform independence.
* Explain one variable and its data type.
* Explain why a particular hard-coded value was selected.
* Change one hard-coded value.
* Predict the new output.
* Explain an arithmetic expression.
* Explain an assignment operator.
* Explain a relational condition.
* Explain a logical condition.
* Explain a compound condition.
* Explain the selected loop.
* Change a `while` loop to `do-while`.
* Change an eligibility rule.
* Add one validation condition.
* Convert integer division to decimal division.
* Explain type casting.
* Replace a suitable condition with a ternary operator.
* Explain pre-increment and post-increment.
* Explain pre-decrement and post-decrement.
* Change the sign using unary minus.
* Remove a logical condition and explain the impact.
* Change one hard-coded menu choice.
* Correct an introduced error.
* Rewrite one small part independently.

---

# Student Completion Checklist

```text
[ ] My repository name is Second-PRD
[ ] I received one requirement
[ ] My requirement is unique within my team
[ ] I created the project-title folder
[ ] I created requirement/requirement.md
[ ] I created src/Main.java
[ ] I created sol/Main.java
[ ] I used hard-coded values only
[ ] I did not use Scanner
[ ] I did not use runtime input
[ ] I used my own variable names
[ ] I used my own values
[ ] I used arithmetic operators
[ ] I used assignment operators
[ ] I used relational operators
[ ] I used logical operators
[ ] I used unary operators where required
[ ] I used a ternary operator where required
[ ] I used conditions
[ ] I used while or do-while
[ ] I handled decimal division correctly
[ ] I tested two different value sets
[ ] I uploaded output-1.png
[ ] I uploaded output-2.png
[ ] My program compiles
[ ] My program runs
[ ] My repository is accessible
[ ] I updated README.md
[ ] I shared my repository URL with the Team Leader
[ ] I can explain the complete program
[ ] I submitted before 6:00 PM
```

---

# Team Leader Completion Checklist

```text
[ ] I completed my own assigned requirement
[ ] Every member received one unique requirement
[ ] No requirement repeats within the team
[ ] Every member used hard-coded values only
[ ] No member used Scanner
[ ] No member used runtime input
[ ] Every repository URL was collected
[ ] Every repository was opened
[ ] Every requirement file was checked
[ ] Every src/Main.java was checked
[ ] Every sol/Main.java was checked
[ ] Both output screenshots were checked
[ ] Every program status was verified
[ ] Every student explained one part
[ ] One hard-coded value was changed during verification
[ ] Every submission time was recorded
[ ] Missing submissions were marked honestly
[ ] Incomplete submissions were marked honestly
[ ] Verification-required cases were identified
[ ] report/report.txt was completed
[ ] The Team Leader repository was pushed before 6:00 PM
[ ] The Team Leader repository URL was shared with the trainer
```

---

# Final Instruction

This activity is compulsory for every student.

Every student must complete the assigned requirement and push the complete repository before **6:00 PM on August 5, 2026**.

The purpose is not only to obtain output.

The purpose is to demonstrate that the student can:

* Understand a requirement
* Select suitable variables
* Create meaningful hard-coded values
* Apply operators correctly
* Use conditions
* Use loops
* Perform decimal calculations
* Test different values
* Correct mistakes
* Use GitHub properly
* Explain the complete program independently

A simple program that the student understands completely is more valuable than an advanced program that the student cannot explain.

Incomplete, copied, inaccessible, late, runtime-input-based, or unexplained submissions will lose credits.

Copied work, false reporting, or complete inability to explain the submitted work may result in negative points and reassessment.

Complete the assigned requirement independently and submit it before **6:00 PM**.
