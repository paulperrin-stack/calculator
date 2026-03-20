# Calculator 🧮

A browser-based calculator built with vanilla HTML, CSS, and JavaScript.

## 🎮 Live Demo

[Open Calculator](https://paulperrin-stack.github.io/calculator/)

## Features

- Addition, subtraction, multiplication, and division
- Decimal point support
- Toggle positive/negative sign (+/-)
- Chained calculations (no need to press = between operations)
- Running expression shown above the main display
- Clear current entry (C) and clear all (AC)
- Division by zero protection

## What I Learned

- Organizing math logic into separate functions (`add`, `subtract`, `multiply`, `divide`)
- Using an object as a lookup table to map operators to functions
- Managing calculator state with variables (`firstNumber`, `currentOperator`, `shouldResetDisplay`)
- Handling edge cases like chained operators, repeated equals, and division by zero
- DOM manipulation and event delegation with `querySelectorAll`

## Built With

- HTML
- CSS
- JavaScript

## Part of

[The Odin Project](https://www.theodinproject.com/) — Foundations curriculum