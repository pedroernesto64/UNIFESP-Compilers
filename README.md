# UNIFESP-Compilers
Final project for the Compilers at UNIFESP (Federal University of São Paulo - Brazil)
Project specifications are described in Enunciado.pdf

# Compilation (Linux)
``gcc ./parser.tab.c ./lex.yy.c ./AAS.c ./TabSimbolos.c -o compiler``

# Usage
Once compiled, run ``./compiler entrada.txt`` in your terminal. The source code (entrada.txt) should be in the C Minus language, as specified in Kenneth C. Louden's book Compiler Construction Principles and Practice. Three example source codes are provided.

This project was done in collaboration with Pedro Pinheiro (https://github.com/pepe20p)
