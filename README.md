# RetroCalcLang Compiler

RetroCalcLang is a production-quality compiler for a programmable calculator language, built for the CS4031 Compiler Construction course.

## How to Run

To run the compiler, use the following command in your terminal:

```cmd
python compiler.py <filename.src>
```

### Examples:
- **Run basic arithmetic**: `python compiler.py samples/arithmetic.src`
- **Run loops and logic**: `python compiler.py samples/loops.src`
- **Run with debug info**: `python compiler.py samples/arithmetic.src --debug`

## Features
- **Lexical Analysis**: Regular expression based tokenization.
- **Syntax Analysis**: Recursive descent parser with operator precedence.
- **Semantic Analysis**: Symbol table and error checking.
- **Intermediate Representation**: Three-Address Code (TAC).
- **Optimization**: Constant Folding and Dead Code Elimination.
- **Execution**: Virtual Machine-based TAC interpreter.

## Requirements
- Python 3.6+ (No external libraries required)
