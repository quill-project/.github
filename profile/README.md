<img src="./quill_tp.svg" height="200px" align="right">

### The Quill Project
The Quill programming language is a high-level, statically typed, garbage collected and compiled programming language. Quill promises simplicity and elegance, but not at the cost of program execution speed.

The Quill Project includes a compiler and a collection of libraries for the Quill programming language. Notable repositories include:
- [`compiler`](https://github.com/quill-project/compiler) - The Quill compiler written in Quill, which acts as a Quill library.
- [`cli`](https://github.com/quill-project/cli) - The Quill command line interface and package manager.
- [`vscode-quill`](https://github.com/quill-project/vscode-quill) - The Quill Visual Studio Code extension.
- [`std-c`](https://github.com/quill-project/std-c) - The C implementation of the Quill standard library.
- [`std-js`](https://github.com/quill-project/std-js) - The Javascript implementation of the Quill standard library.
- [`std`](https://github.com/quill-project/std) - Functionality of the Quill standard library shared across all compiler backends. Should not be used directly - instead, a backend-specific implementation should be used (such as [`std-c`](https://github.com/quill-project/std-c)).
- [`bootstrap`](https://github.com/quill-project/bootstrap) - The now obsolete bootstrap compiler for Quill written in Javascript used to originally get the language running.