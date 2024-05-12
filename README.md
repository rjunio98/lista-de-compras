# Lista de Compras Dinâmica

Este é um mini projeto para praticar conceitos fundamentais de React, como componentes, estado, renderização condicional e manipulação de eventos. O objetivo é criar uma lista de compras dinâmica que permite adicionar itens, marcá-los como concluídos e excluí-los.

## Como usar

1. Clone este repositório
2. Instale as dependências com `npm install`
3. Inicie o servidor de desenvolvimento com `npm run dev`

## Funcionalidades

### Formulário

- Adicione itens à lista de compras ao submeter o formulário
- Limpe o formulário após adicionar um item
- Foco automático no primeiro campo do formulário após adicionar um item

### Concluir Item

- Marque um item como concluído ao clicar no botão correspondente
- O item marcado será movido para a lista de "Itens já comprados"
- O texto do item marcado será riscado e terá uma cor mais clara
- O ícone de "A fazer" (círculo vazio) será substituído pelo ícone de "Feito" (check)

### Excluir Item

- Exclua um item ao clicar no ícone de lixeira

### Componentização

- Organize o código em componentes para manter a legibilidade e reutilização de código

## Pré-requisitos

Conhecimento básico de React, incluindo JSX, componentes e props.