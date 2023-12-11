# O que é TypeScript?

- TypeScript é um **superset** para a linguagem JavaScript;
- Ou seja, adiciona funções ao JavaScript, como a **declaração de tipos** de
  variável;
- Pode ser utilizado com **frameworks/libs**, como: Express e React;
- Precisa ser **compilado em JavaScript**, não executamos TS;
- Desenvolvido e mantido pela Microsoft;

# Por que TypeScript?

- Adiciona **confiabilidade** ao programa (tipos);
- Provê novas funcionalidades a JS, como **Interfaces**;
- Com TS podemos **verificar os erros antes da execução do código**, ou
  seja, no desenvolvimento;
- Deixa JavaScript **mais explícito**, diminuindo a quantidade de bugs;
- Por estes e outros motivos **perdemos menos tempo com debug;**

## Instalando o TypeScript

Para instalar o **TypeScript**, utilizamos o npm;

```bash
  npm install -g typescript
```

A partir da instalação temos como executar/compilar TS em qualquer
local da nossa máquina, com o comando tsc;

```bash
  tsc meuArquivo.ts
```

Isso gerará um arquivo **JavaScript** correspondente, por exemplo, **meuArquivo.js**.
