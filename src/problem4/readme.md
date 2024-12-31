
# Problem4

This is a TypeScript project with Jest for testing. It includes configurations to run TypeScript code and unit tests using Jest.

## Installation

To get started, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yuvraj-singh-codes/code-challenge.git
cd problem4
npm install
```

## Scripts

This project provides the following npm scripts:

- `start`: Runs the application using `ts-node`. It executes the `run.ts` file.
    ```bash
    npm start
    ```

- `test`: Runs Jest to execute unit tests.
    ```bash
    npm test
    ```

- `test:watch`: Runs Jest in watch mode, which will re-run tests whenever changes are made.
    ```bash
    npm run test:watch
    ```

## Dependencies

This project uses the following dependencies:

- `@types/jest`: TypeScript type definitions for Jest.
- `@types/node`: TypeScript type definitions for Node.js.
- `jest`: Testing framework for JavaScript and TypeScript.
- `ts-jest`: Jest preset to support TypeScript.
- `ts-node`: TypeScript execution engine for Node.js.
- `typescript`: TypeScript language and compiler.