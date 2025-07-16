# TypeScript CLI Project

This is a simple TypeScript CLI project that demonstrates basic setup, building, and running a TypeScript-based command-line application.

## Prerequisites
- Node.js (v14 or above recommended)
- npm (comes with Node.js)

## Setup
Install dependencies:
```bash
npm install
```

## Development Mode
Run the CLI directly using ts-node (TypeScript execution):
```bash
npm start
```

## Production/Build Mode
1. Build the project (compile TypeScript to JavaScript):
    ```bash
    npx tsc
    ```
2. Run the compiled JavaScript:
    ```bash
    node index.js
    ```

## What it does
The CLI currently calculates the sum of two numbers and prints the result.

---
Feel free to modify `index.ts` to add more CLI features! 