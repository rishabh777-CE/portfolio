---
title: CodeFox
date: 2023/10/12
description: View project details.
tag: web development
author: You
---

# CODEFOX

 link: https://github.com/rishabh777-CE/CodeFox

## project desciption

#### CodeFox is a simple online-judge by which user can add programming problems and solve them. Only supports C, C++, Python language.User can login in with google. Used PassportJS for auth.Signed In user can add new Problem with custom testcase. He can also edit and delete the problem.Any user can run his code in the problem page. Only signed in user can submit the code.User can see if the problem verdit is accepted, wrong answer or TLE after submitting the code.User can see his previous submission in a particular problem. He can also download the codes

Key Features:
ntegrated Google login (PassportJS) for
user authentication. 
Managed problems with custom
test cases; users can submit code, view verdicts, and
access previous submissions.
Leveraged Docker container for code execution.
Actively learning to calculate code complexity for
future enhancements.

Technology Stack:

    Frontend: Built with React, the user interface is responsive, interactive, and user-friendly. It supports dark mode and fullscreen mode options for customization.

    Backend: Powered by Node.js and Express.js, the backend server handles user authentication, code sharing, and real-time communication through WebSocket using Socket.io.

    Database: MongoDB is used to store user information and code snippets securely. This ensures that code sessions can be retrieved and accessed by users with the unique links.
    
    Docker:   Docker container for code execution.
    
    Bull Queue: Job scheduling to solve the problem of multiple submission request. 

