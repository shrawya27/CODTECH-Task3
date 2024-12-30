Name:Shrawya.A.K
Company:CODTECH IT SOLUTIONS
ID:CT08FOX
Domain:C++ programming
Duration:december 20th,2024 to january 20th,2025
Mentor:Neela Santhosh Kumar

Overview of project:
Objective:
To create a Student Management System in C++ that enables educational institutions or users to manage student data efficiently. The system should support registering students, maintaining records, calculating grades, and providing editing and deletion functionalities.

Key Features
Student Registration:

Add new student details such as:
ID
Name
Age
Marks for subjects
Course or program
Maintain Student Records:

Store student information in a structured manner.
Display individual or all student records.
Grade Calculation:

Compute grades based on average marks using standard grading criteria:
A (90–100), B (80–89), C (70–79), D (60–69), F (below 60).
Editing Student Details:

Update the name, age, and marks of an existing student.
Deleting Student Records:

Remove a student's information from the system by using their ID.
Display Functionality:

View a list of all students with their details, including grades.
Interactive Menu:

Provide a user-friendly, menu-driven interface to interact with the system.
System Design
Class Structure:

Student Class:
Represents a single student.
Attributes: ID, name, age, marks, and grade.
Methods: Grade calculation, display, and setters/getters.
StudentManagement Class:
Manages a collection of students.
Methods: Add, edit, delete, and display students.
Data Storage:

Use std::vector for dynamic storage of students in memory.
Optionally, implement file handling for persistent storage.
Menu-Driven Approach:

Continuously prompt the user with options to perform operations like adding, editing, or viewing student records until they choose to exit.
Planned Features and Implementation
Adding Students:

Prompt the user to enter details like ID, name, and marks.
Validate inputs (e.g., unique ID, non-negative marks).
Editing Students:

Allow modifications to existing student records by their ID.
Deleting Students:

Find and remove a student by ID.
Calculating Grades:

Use a formula to compute grades based on average marks.
Displaying Students:

Show all students with their attributes in a formatted table.
Input Validation:

Ensure valid entries for numbers, names, and marks.
Development Steps
Define Classes:

Create a Student class for individual records.
Create a StudentManagement class for managing operations on students.
Implement Menu Logic:

Provide options for:
Adding a new student.
Editing existing student details.
Deleting a student.
Displaying all student records.
Exiting the program.
Develop Core Functions:

Write methods for each feature, ensuring encapsulation and reusability.
Error Handling:

Handle cases where student IDs are not found or invalid input is entered.
Testing:
