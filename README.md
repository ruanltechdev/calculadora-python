# Calculadora Pro

Aplicação desktop de calculadora feita em Python e Tkinter. Este repositório contém uma cópia independente do projeto que já estava na pasta de projetos do repositório de perfil.

## Funcionalidades

- Adição, subtração, multiplicação e divisão
- Decimais, parênteses, porcentagem, potência e raiz quadrada
- Histórico disponível enquanto a aplicação está aberta
- Atalhos: Enter calcula, Esc limpa e Backspace apaga
- Avaliação restrita da expressão matemática usando a AST do Python, sem `eval()`
- Tratamento de expressões inválidas e divisão por zero

## Requisitos

- Python 3.10 ou superior
- Tkinter, normalmente incluído na instalação do Python para Windows

## Como executar

```bash
python calculadora.py
```

O histórico é mantido apenas na memória e desaparece ao fechar a aplicação. A pasta `screenshots/` será usada para capturas de tela reais da interface.

## Próximas melhorias

- Adicionar testes automatizados para a lógica matemática
- Incluir uma captura da aplicação em execução
- Persistir o histórico entre sessões

