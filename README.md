
## About the project

This project allows you to compile your Pascal files into RISC-V assembly. It can also be used as syntax analyzer (parser) by excluding RISC-V code generation out of the code.


## Features

- Syntax analizer
- RISC-V code generation
- Register allocation via Linear Scan algorithm
- Simplification of constants in arithmetic expressions before code generation


## Installation and launch

Make sure you have OCaml and Dune installed
```bash
  sudo apt install opam
  opam init 
  opam install dune
```

Clone the project (or you can download it from Releases)

```bash
  git clone https://github.com/p1onerka/robbing_cowavans
```

Go to the project directory

```bash
  cd robbing_cowavans
```

Build Dune and run project using path to your source code file

```bash
  dune build 
  dune exec ./bin/main.exe *your path to source file*
```
The generated assembly file will be located in "out" folder


## File structure

```
bin
├── main
│  │
│  ├── model
│  │  ├── algorithms
lib
├── CCHeap
├── codegen RISCV
│  ├── codegen
│  ├── life intervals
├── helper functions
│  ├── binders (for error treatment)
├── parser
│  ├── constants simplification
│  ├── error processing
│  ├── expression parser
│  ├── file reading
│  ├── statement parser
│  ├── types
out
├── your generated code located here
test
├──
```


## Example of usage

```
```


## Running tests

```bash
```


## Credits

[OCaml-containers](https://github.com/c-cube/ocaml-containers) for using CCHeap


## Developers and contacts

- [@p1onerka](https://github.com/p1onerka) (tg @p10nerka)
- [@Szczucki](https://github.com/Szczucki) (tg @szcz00)


## Feedback

If you have any feedback, please reach out to us at xeniia.ka@gmail.com or 


## License

The project is distributed under [MIT](https://choosealicense.com/licenses/mit/) license. Check [LICENSE](https://github.com/p1onerka/robbing_cowavans/blob/main/LICENSE) for more information.


