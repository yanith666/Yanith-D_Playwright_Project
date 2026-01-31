# IT23747968_PLAYWRIGHT_PROJECT
# IT3040 – Assignment 1  
## Automated Testing Using Playwright (TypeScript)

### Degree Programme
BSc (Hons) in Information Technology – Year 3  

### Module
IT3040 – IT Project Management  

### Semester
Semester 1  

### Student
Name: <Ravindu D M Y>  
Registration Number: <IT23747968>  

---

##1. Project Overview

This repository presents an automated testing framework built using Playwright with TypeScript, designed to test a real-world language transliteration application.

Chosen Assignment Option:
Option 1 – Singlish to Sinhala Transliteration

Application Under Test:
https://www.swifttranslator.com/

The primary goal of this project is to evaluate:
  -The correctness of Singlish-to-Sinhala transliteration
  -The system’s resilience when handling diverse input types
  -The stability, responsiveness, and usability of the user interface

All testing activities are strictly confined to functional and UI-level behavior, in line with the assignment requirements.

##2. Testing Coverage

The automated test suite includes validation of:
  -Basic, compound, and complex sentence structures
  -Question-based and command-based sentences
  -Affirmative and negative expressions
  -Different tense forms (past, present, and future)
  -Usage of pronouns and plural nouns
  -Common everyday conversational phrases
  -Formal and informal language styles
  -Inputs containing both Singlish and English
  -Technical terms and brand-specific English words
  -Numerical values, dates, time formats, and currency symbols
  -Input formatting variations such as spacing, line breaks, and paragraphs
  -Robustness cases including merged words, spelling errors, slang, and emojis
  -Real-time generation of Sinhala output through the user interface
## 3. Test Case Summary

| Test Category | Number of Test Cases |
|--------------|----------------------|
| Positive Functional Tests | 24 |
| Negative Functional Tests | 10 |
| UI Test Cases | 1 |
| **Total** | **35** |

---

## 4. Technology Stack

- Playwright  
- TypeScript  
- Node.js  
- Visual Studio Code  

---

## 5. Project Structure

IT23747968_PLAYWRIGHT_PROJECT/
│
├── e2e/
│
├── node_modules/
│
├── playwright-report/
│   ├── data/
│   └── index.html
│
├── test-results/
│
├── tests/
│   ├── IT23747968 - IT3040_TestCases.xlsx
│   ├── IT23747968 - transliteration.spec.ts
│   ├── IT23747968-generate_excel.js
│   └── IT23747968-generate_excel.ts
│
├── README.md
├── .gitignore
├── package.json
├── package-lock.json
├── playwright.config.ts
└── playwright.config.js


---

## 6. Prerequisites

Before running the tests, ensure the following are installed:

- **Node.js (LTS version)**  
  Download: https://nodejs.org/

- **Git** (optional, for cloning the repository)  
  Download: https://git-scm.com/

- **Internet connection** (required to access the test application)

---

## 7. Installation Instructions

### Step 1: Clone the Repository

git clone <your-github-repository-link>

### Step 2: Navigate to the Project Directory

cd IT3040_Assignment1

### Step 3: Install Dependencies

npm install

## 8. Running the Automated Tests

Run All Tests - npx playwright test

View the HTML Test Report - npx playwright show-report
