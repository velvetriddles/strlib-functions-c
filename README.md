# s21_string

## Overview
This is an educational project aimed at implementing a custom version of the string.h library in C. The project includes implementations of various string manipulation functions, as well as partial implementations of sprintf and sscanf functions.

## Educational Purpose
This project is designed to deepen understanding of:
- C programming language
- String manipulation in C
- Library creation in C
- Unit testing
- Code coverage analysis
- Makefile usage

## Features
- Implementation of basic string.h functions
- Partial implementation of sprintf
- Unit tests using the Check framework
- Code coverage analysis using gcov
- Support for both Linux and macOS environments

## Building and Testing
Use the provided Makefile for building the library and running tests:
```
make all          # Build the library and run tests
make test         # Run unit tests
make gcov_report  # Generate code coverage report
make clean        # Clean up build artifacts
```

## Project Structure
- `s21_*.c` files: Implementation of string functions
- `s21_string.h`: Header file for the library
- `unit_test/`: Contains unit tests
- `test/`: Additional tests (e.g., for sprintf)

## Note
This is a learning project and not intended for production use. It's part of an educational curriculum to understand low-level string manipulation in C.