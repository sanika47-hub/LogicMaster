# LogicMaster

## Gamified Logic Learning and Automated Assessment Platform

LogicMaster is a gamified web-based application designed to help students improve their logical reasoning, problem-solving, and programming logic skills through interactive challenges.

The platform combines learning with gamification by allowing users to solve logic-based problems, receive automated feedback, and track their progress.

## Features

* Gamified learning through interactive logic-based challenges
* Multiple types of logical and programming problems
* Challenges with varying difficulty levels
* Automated evaluation of user submissions
* Immediate feedback on submitted solutions
* Score and progress tracking
* Modular and extensible project architecture
* Automated testing for core modules

## Technology Stack

### Frontend

* HTML
* CSS
* JavaScript
* Node.js-based tooling

### Backend

* Node.js
* Express.js

### Testing

* Jest

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm

## Project Structure

```text
LogicMaster/
│
├── backend/
│   ├── server.js
│   └── ...
│
├── package/
│   └── ...
│
├── proof.js
├── proof.test.js
├── proofChallenges.js
│
├── parser.js
├── parser.test.js
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

The exact structure may vary depending on the modules implemented by different team members.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/sanika47-hub/LogicMaster.git
```

### 2. Navigate to the Project Directory

```bash
cd LogicMaster
```

### 3. Install Dependencies

If the project uses the root `package.json`:

```bash
npm install
```

If the backend contains a separate `package.json`:

```bash
cd backend
npm install
```

## Running the Project

Start the application using:

```bash
npm start
```

Alternatively, if the backend is configured to run directly:

```bash
node server.js
```

The application can then be accessed through the local server address displayed in the terminal.

## Running Tests

The project contains automated tests for important modules.

Run all tests using:

```bash
npm test
```

To run individual test files:

```bash
npm test -- parser.test.js
```

```bash
npm test -- proof.test.js
```

## Project Objective

The primary objective of LogicMaster is to make logic and problem-solving practice more interactive and engaging.

Traditional learning methods often rely on static exercises and manual evaluation. LogicMaster provides an interactive approach in which learners can:

1. Select a challenge.
2. Attempt the problem.
3. Submit their solution.
4. Receive automated evaluation.
5. Analyze their result.
6. Progress toward more challenging problems.

## Core Modules

### Parser Module

The parser module processes and interprets the required input or logical expressions used by the application.

### Proof Module

The proof module handles proof-related functionality and validates solutions according to the defined rules.

### Challenge Module

The challenge module provides logic problems for users to solve and forms an important part of the gamified learning experience.

### Backend Module

The backend manages server-side functionality and provides the services required by the application.

## Future Scope

The project can be further enhanced with:

* User authentication and profiles
* Leaderboards and rankings
* Difficulty-based progression
* Badges and achievement systems
* Daily challenges
* Personalized challenge recommendations
* Expanded challenge database
* Detailed performance analytics
* Additional automated evaluation mechanisms
* Responsive mobile interface

## Project Information

**Project:** LogicMaster
**Project Type:** Gamified Application / Automated System Implementation
**Purpose:** Academic Project
**Course:** ISE-2

## License

This project has been developed for academic purposes.
