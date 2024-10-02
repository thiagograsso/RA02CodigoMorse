# Árvore Binária de Código Morse

Este projeto implementa uma árvore binária para armazenar e buscar caracteres representados por código Morse. A árvore permite inserir letras do alfabeto e números, e buscar seus valores correspondentes utilizando a notação Morse.

## Estrutura do Projeto

O projeto é composto por três classes principais:

- **`Nodo`**: Representa um nó na árvore binária, contendo um caractere e referências para os filhos esquerdo e direito.
- **`ArvoreBinariaMorse`**: Gerencia a árvore binária, permitindo a inserção de caracteres e a busca de caracteres a partir de sequências de código Morse.
- **`Main`**: Contém a lógica principal do programa, incluindo a inserção dos caracteres na árvore e a interação com o usuário.

## Funcionalidades

- **Inserção**: Permite inserir letras e números de acordo com suas representações em código Morse.
- **Busca**: Permite buscar um caractere correspondente a uma sequência de código Morse fornecida pelo usuário.
- **Exibição da Árvore**: Exibe a estrutura da árvore binária de forma hierárquica.
- **Validação de Entrada**: Garante que a entrada do usuário contenha apenas os caracteres válidos (`.` e `-`).

## Código Morse

A tabela abaixo resume as representações de letras e números em código Morse:

| Caractere | Código Morse |
|-----------|--------------|
| A         | .-           |
| B         | -...         |
| C         | -.-.         |
| D         | -..          |
| E         | .            |
| F         | ..-.         |
| G         | --.          |
| H         | ....         |
| I         | ..           |
| J         | .---         |
| K         | -.-          |
| L         | .-..         |
| M         | --           |
| N         | -.           |
| O         | ---          |
| P         | .--.         |
| Q         | --.-         |
| R         | .-.          |
| S         | ...          |
| T         | -            |
| U         | ..-          |
| V         | ...-         |
| W         | .--          |
| X         | -..-         |
| Y         | -.--         |
| Z         | --..         |
| 0         | -----        |
| 1         | .----        |
| 2         | ..---        |
| 3         | ...--        |
| 4         | ....-        |
| 5         | .....        |
| 6         | -....        |
| 7         | --...        |
| 8         | ---..        |
| 9         | ----.        |

