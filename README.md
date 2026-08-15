# ALX Low-Level Programming

> A structured collection of C programming projects completed during the ALX Software Engineering curriculum, covering the foundations of low-level programming, algorithms, memory management, data structures, and systems-oriented development.

![Language](https://img.shields.io/badge/language-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Curriculum](https://img.shields.io/badge/curriculum-ALX-000000?style=flat-square)
![Environment](https://img.shields.io/badge/compiler-GCC-374151?style=flat-square&logo=gnu&logoColor=white)
![Style](https://img.shields.io/badge/style-Betty-2563EB?style=flat-square)

## Table of Contents

- [Repository Overview](#repository-overview)
- [Learning Path](#learning-path)
- [Folder Map](#folder-map)
- [Core Concepts](#core-concepts)
- [Repository Requirements](#repository-requirements)
- [Compilation Workflow](#compilation-workflow)
- [Betty Style and Documentation](#betty-style-and-documentation)
- [How to Use This Repository](#how-to-use-this-repository)
- [Suggested Review Process](#suggested-review-process)
- [Project Status](#project-status)
- [References](#references)

## Repository Overview

This repository contains a progressive set of C programming projects. Each directory focuses on a specific stage of the low-level programming journey, beginning with basic syntax and control flow and continuing through pointers, recursion, memory allocation, linked lists, file input/output, hash tables, dynamic libraries, and search algorithms.

The repository is organized as a learning path rather than a collection of unrelated exercises. Earlier projects establish the language fundamentals that are required by later projects. For example, understanding pointers and arrays is essential before studying linked lists, and understanding memory allocation is necessary before working safely with dynamic data structures.

The goal is not only to produce programs that compile. Each solution should demonstrate clear reasoning, correct memory management, predictable behavior, readable code, and compliance with the project's required coding style.

> **Learning principle:** understand the memory model and the execution flow behind each program. A short solution is valuable only when its behavior can be explained and verified.

## Learning Path

The folders are arranged by subject number. The numerical order represents the intended progression of the curriculum, while the concepts become increasingly focused on memory, abstraction, data structures, and performance.

| Stage | Main focus | Skills developed |
|---|---|---|
| Foundations | Syntax, variables, functions, and control flow | Basic C programs, compilation, conditionals, loops, and function design. |
| Memory and abstraction | Pointers, arrays, strings, recursion, and dynamic allocation | Address manipulation, stack behavior, heap allocation, and defensive programming. |
| Data structures | Singly linked lists, doubly linked lists, hash tables, and file data | Dynamic structures, ownership, traversal, insertion, deletion, and lookup. |
| Build and runtime systems | Static libraries, makefiles, and dynamic libraries | Linking, build automation, symbol resolution, and shared objects. |
| Algorithms | Search methods and complexity | Sequential search, binary search, and the relationship between data order and performance. |

## Folder Map

Each project directory should be treated as an independent learning unit. Open the directory to view its source files, task implementations, test files where provided, and any local documentation. If a folder contains its own `README.md`, use that file as the detailed task reference for the directory.

| Directory | Topic | What to review inside the folder |
|---|---|---|
| [`0x00-hello_world`](./0x00-hello_world) | Hello, World | Preprocessing, compilation, output, and the basic structure of a C program. |
| [`0x01-variables_if_else_while`](./0x01-variables_if_else_while) | Variables, conditionals, and loops | Declarations, operators, `if`, `else`, `while`, and control flow. |
| [`0x02-functions_nested_loops`](./0x02-functions_nested_loops) | Functions and nested loops | Function prototypes, scope, reusable logic, and nested iteration. |
| [`0x03-debugging`](./0x03-debugging) | Debugging | Reading compiler messages, isolating faults, and correcting program behavior. |
| [`0x04-more_functions_nested_loops`](./0x04-more_functions_nested_loops) | More functions and loops | Decomposition, nested control flow, and code organization. |
| [`0x05-pointers_arrays_strings`](./0x05-pointers_arrays_strings) | Pointers, arrays, and strings | Addresses, dereferencing, array traversal, and C string conventions. |
| [`0x06-pointers_arrays_strings`](./0x06-pointers_arrays_strings) | More pointers, arrays, and strings | Memory access, string manipulation, and pointer-based algorithms. |
| [`0x07-pointers_arrays_strings`](./0x07-pointers_arrays_strings) | Advanced pointer practice | Multidimensional arrays, pointer relationships, and function parameters. |
| [`0x08-recursion`](./0x08-recursion) | Recursion | Base cases, recursive decomposition, call stacks, and termination. |
| [`0x09-static_libraries`](./0x09-static_libraries) | Static libraries | Object files, archives, symbol tables, and library linking. |
| [`0x0A-argc_argv`](./0x0A-argc_argv) | Command-line arguments | `argc`, `argv`, input validation, and command-line program design. |
| [`0x0B-malloc_free`](./0x0B-malloc_free) | Dynamic memory allocation | `malloc`, `free`, allocation failures, ownership, and memory leaks. |
| [`0x0C-more_malloc_free`](./0x0C-more_malloc_free) | More allocation and deallocation | `calloc`, `realloc`, allocation strategies, and robust error handling. |
| [`0x0D-preprocessor`](./0x0D-preprocessor) | Preprocessor | Macros, header guards, conditional compilation, and preprocessing stages. |
| [`0x0E-structures_typedef`](./0x0E-structures_typedef) | Structures and `typedef` | User-defined records, aliases, initialization, and data modeling. |
| [`0x0F-function_pointers`](./0x0F-function_pointers) | Function pointers | Callbacks, dispatch tables, and passing behavior as data. |
| [`0x10-variadic_functions`](./0x10-variadic_functions) | Variadic functions | `stdarg.h`, variable argument lists, and interface design. |
| [`0x12-singly_linked_lists`](./0x12-singly_linked_lists) | Singly linked lists | Nodes, traversal, insertion, deletion, and dynamic ownership. |
| [`0x13-more_singly_linked_lists`](./0x13-more_singly_linked_lists) | More singly linked lists | List manipulation, safe deletion, reversal, and cycle-related reasoning. |
| [`0x14-bit_manipulation`](./0x14-bit_manipulation) | Bit manipulation | Binary representation, masks, shifts, flags, and bitwise operators. |
| [`0x15-file_io`](./0x15-file_io) | File input/output | File descriptors, system calls, permissions, reading, writing, and closing. |
| [`0x17-doubly_linked_lists`](./0x17-doubly_linked_lists) | Doubly linked lists | Forward and backward traversal, insertion, deletion, and pointer integrity. |
| [`0x18-dynamic_libraries`](./0x18-dynamic_libraries) | Dynamic libraries | Shared objects, `LD_LIBRARY_PATH`, runtime linking, and exported symbols. |
| [`0x1A-hash_tables`](./0x1A-hash_tables) | Hash tables | Hash functions, collision handling, chaining, insertion, lookup, and deletion. |
| [`0x1C-makefiles`](./0x1C-makefiles) | Makefiles | Targets, dependencies, variables, rebuild logic, and reproducible builds. |
| [`0x1E-search_algorithms`](./0x1E-search_algorithms) | Search algorithms | Linear search, binary search, complexity, and algorithm selection. |

> **Directory-specific documentation:** When a folder contains its own README, start there. The root README explains the repository as a whole; each local README should explain the tasks, constraints, and implementation details specific to that folder.

## Core Concepts

### Compilation and execution

C source code is translated into an executable through several stages: preprocessing, compilation, assembly, and linking. A command such as `gcc main.c -o main` produces an executable named `main` when the source is valid and the required symbols can be resolved.[1]

Understanding these stages makes compiler errors easier to interpret. A preprocessing problem usually concerns macros or included headers, a compilation problem concerns C syntax or types, and a linker problem commonly concerns missing function definitions or libraries.

### The `main` function

The `main` function is the entry point of a hosted C program. It receives command-line input through `argc` and `argv` when those parameters are declared, and it returns a status code to the operating system. Returning `0` conventionally indicates successful termination, while a non-zero value communicates an error or another status.[1]

### Pointers and memory

A pointer stores an address. Dereferencing a pointer accesses the object located at that address. This mechanism allows functions to modify caller-owned data, supports arrays and strings, and forms the basis of linked data structures.

Pointer operations must respect object lifetime and bounds. Dereferencing `NULL`, using an uninitialized pointer, accessing memory after `free`, or writing beyond an allocated object produces undefined behavior. The compiler may not detect every instance, so careful ownership rules and runtime tools are important.

### Dynamic allocation

Dynamic allocation reserves memory during program execution. `malloc` returns a block of uninitialized memory, while `calloc` allocates and initializes an array of objects. `realloc` changes the size of an existing allocation, possibly moving it to a new address. Every successful allocation must have a clear owner and a corresponding release through `free` when the memory is no longer needed.[2]

### Static and dynamic libraries

A static library is an archive of object files that is linked into an executable during the build process. A dynamic library is loaded separately, either when the program starts or when the program requests it at runtime. Libraries reduce duplication and encourage reusable interfaces, but they require correct declarations, symbols, paths, and link options.[3]

### Data structures and algorithms

A data structure determines how information is represented and accessed. An algorithm determines how a problem is solved. The right combination depends on the operation that matters most: traversal, insertion, deletion, lookup, ordering, or memory usage.

For example, linear search examines elements sequentially and works on unsorted data. Binary search can be substantially faster, but it requires an ordered search space and a correct method for narrowing the interval. The implementation should therefore explain both its result and its expected complexity.

## Repository Requirements

The original project requirements specify a restricted development environment. Follow the requirements attached to the relevant cohort and task, even if your current compiler is newer.

| Requirement | Expected configuration |
|---|---|
| Allowed editors | `vi`, `vim`, or `emacs`, unless the task instructions specify otherwise. |
| Target environment | Ubuntu 14.04 LTS with GCC 4.8.4 for the original task set. |
| Language | C. |
| Style | Betty coding style and Betty documentation checks. |
| Portability | Avoid compiler-specific behavior unless explicitly required by the task. |
| Repository hygiene | Keep source files, headers, tests, and documentation organized. Remove generated binaries and temporary files when the task requires it. |

> Toolchain note: the stated compiler and Ubuntu version belong to the original task requirements. On a modern machine, use the official project environment or container when exact compatibility is required. Do not assume that code accepted by a recent compiler will behave identically under an older toolchain.

## Compilation Workflow

Compile the smallest possible unit first. This makes compiler output easier to interpret and reduces the number of possible causes when an error appears.

### Basic compilation

```bash
gcc main.c -o main
./main
```

### Recommended warnings

For personal development, enable warnings and debugging information:

```bash
gcc -Wall -Wextra -Werror -pedantic -g main.c -o main
```

The exact flags required for a task may differ. The project checker and task instructions take priority over personal preferences.

### Multiple source files

```bash
gcc -Wall -Wextra -Werror -pedantic -g main.c helpers.c -o program
./program
```

### Headers and include paths

Use header files for declarations shared across source files. Include the appropriate standard-library header for every function used. For example:

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
```

Keep declarations in headers and definitions in `.c` files. Use include guards to prevent accidental multiple inclusion:

```c
#ifndef PROJECT_HEADER_H
#define PROJECT_HEADER_H

/* Declarations go here. */

#endif /* PROJECT_HEADER_H */
```

### Static-library example

```bash
gcc -c *.c
ar rcs libproject.a *.o
gcc main.c -L. -lproject -o main
```

The library name `libproject.a` is referenced with `-lproject`; the `lib` prefix and `.a` suffix are supplied by the linker convention.

### Dynamic-library example

```bash
gcc -fPIC -shared -o libproject.so *.c
gcc main.c -L. -lproject -o main
LD_LIBRARY_PATH=. ./main
```

Use the exact library name, exported symbols, and runtime path required by the relevant project.

## Betty Style and Documentation

Betty is used to check the required coding and documentation style. Run the checks from the directory containing the relevant source files:

```bash
betty-style.pl *.c *.h
betty-doc.pl *.c *.h
```

Depending on the task, you may need to check subdirectories as well. A clean style result does not prove that a program is correct; it only confirms that the formatting and documentation rules were satisfied.

Good C documentation explains the purpose of a function, its parameters, its return value, and any important side effects. Comments should clarify reasoning or non-obvious constraints rather than repeat the code line by line.

## How to Use This Repository

Begin with the folder that matches the topic you are studying. Read its local README, inspect the prototypes and task requirements, and identify the expected behavior before writing code.

A productive workflow is:

1. Read the task and identify inputs, outputs, constraints, and forbidden functions.
2. Inspect the existing files and locate the required prototypes or headers.
3. Write the smallest correct implementation.
4. Compile with the required command and address warnings immediately.
5. Test normal input, boundary input, invalid input, and empty input where relevant.
6. Check memory behavior when pointers or dynamic allocation are involved.
7. Run Betty checks on all changed files.
8. Review the final diff and remove generated artifacts that should not be committed.

The folder links in the [Folder Map](#folder-map) are intended to make navigation direct from the root README. Replace or extend the links if your local repository uses different names.

## Suggested Review Process

A review should assess more than whether the output matches one example. Use the following questions:

| Review area | Questions to ask |
|---|---|
| Correctness | Does the program satisfy the task for valid and invalid input? |
| Memory | Is every allocation checked, and is every owned allocation released exactly once? |
| Bounds | Are arrays, strings, file buffers, and indexes accessed within valid limits? |
| Interfaces | Do function prototypes, return values, and error paths communicate clearly? |
| Style | Does the code pass Betty and remain readable without unnecessary complexity? |
| Portability | Does the implementation rely on behavior outside the task's required environment? |
| Testing | Were edge cases tested rather than only the example shown in the task? |
| Documentation | Can another student understand the purpose and constraints of the implementation? |

For memory-focused projects, tools such as AddressSanitizer, Valgrind, and the compiler's warning options can provide additional feedback when they are available in the development environment. They complement, but do not replace, the required checker.

## Project Status

The repository currently contains projects through search algorithms and includes the following learning areas:

- C fundamentals and control flow.
- Functions, nested loops, and debugging.
- Pointers, arrays, strings, and recursion.
- Static libraries, command-line arguments, and dynamic allocation.
- Preprocessor directives, structures, function pointers, and variadic functions.
- Singly and doubly linked lists.
- Bit manipulation and file descriptors.
- Dynamic libraries, hash tables, makefiles, and search algorithms.

Update this section as new project directories are added. A useful practice is to mark each folder as **in progress**, **complete**, or **under review** in the folder's own README rather than maintaining two conflicting status lists.

## References

[1]: https://en.cppreference.com/w/c/language/main_function "C main function and program startup - cppreference"
[2]: https://en.cppreference.com/w/c/memory "C memory management - cppreference"
[3]: https://gcc.gnu.org/onlinedocs/gcc/ "GCC documentation"
[4]: https://www.gnu.org/software/make/manual/make.html "GNU Make Manual"
[5]: https://github.com/hs-hq/Betty "Betty coding-style and documentation checker"

## Author

Prepared for an ALX Low-Level Programming repository. Replace this line with your name, cohort, GitHub profile, and repository link before publishing.

> Learn the language, understand memory, respect the toolchain, and build from first principles.

