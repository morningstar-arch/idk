# Programming Fundamentals - Lab 03

**Student Name:** Your Name  
**Roll Number:** Your Roll Number  
**Lab Title:** Control Structures and Iteration in C  

---

## Introduction
This repository contains the C programs and tasks completed for Lab 03. The primary focus of this lab is implementing control flow, loop structures (`while`, `nested loops`), and performing basic manual string manipulation without standard helper libraries.

## Lab Objectives
1. Understand and implement nested control structures in C.
2. Handle input buffer issues during dynamic terminal execution using `scanf`.
3. Process multi-student exam marks and evaluate conditions using logical operators (`OR` / `AND`).
4. Implement manual character-by-character string comparisons without standard header files.

## Topics Covered
* Control Flow Statements (`if`, `if-else`)
* `while` and Nested Loops
* Terminal I/O and Buffer Management (`scanf`, `getchar`)
* Arrays and String Traversal
* Logical Operators (`||`, `&&`)

## Key Concept Insight
> "Controlling input buffers using proper format specifiers like `scanf(" %d", &var)` is essential to prevent infinite loops during C program execution."

## Sample Code Snippet
To clear the input buffer manually in C, use the inline loop `while (getchar() != '\n');`.

## Completed Tasks
- [x] Task 1: Implemented nested `while` loops for multi-student mark processing.
- [x] Task 2: Resolved terminal input buffer bugs and infinite loop issues.
- [x] Task 3: Created manual character-by-character string comparison logic.
