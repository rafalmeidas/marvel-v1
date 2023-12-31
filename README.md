[![Marvel V1](https://github.com/rafalmeidas/marvel-v1/actions/workflows/front-end-tests.yml/badge.svg)](https://github.com/rafalmeidas/marvel-v1/actions/workflows/front-end-tests.yml)

# 👋 marvel-v1

O projeto 'marvel-v1' é uma aplicação que foi desenvolvida como parte de um teste para uma posição como desenvolvedor front-end na Objective. O objetivo principal da aplicação é permitir que os usuários pesquisem perfis de desenvolvedores no GitHub.

O 'marvel-v1' é uma aplicação prática e funcional que demonstra habilidades de desenvolvimento front-end, incluindo a integração com a API da Marvel e a criação de interfaces de usuário intuitivas e responsivas. O aplicativo visa proporcionar uma experiência simples e eficaz para os usuários que desejam explorar os personagens do universo Marvel.

## 📚 Índice

- [ℹ️ Sobre](#ℹ%EF%B8%8F-sobre)

- [✨ Recursos](#-recursos)

- [🛠️ Pré-requisitos](#%EF%B8%8F-pré-requisitos)

- [⚙️ Instalação](#%EF%B8%8F-instalação)

- [🧪 Testar](#-testar)

- [🚀 Como Usar](#-como-usar)

- [🤝 Contribuição](#contribuição)

- [📝 Licença](#-licença)

## ℹ️ Sobre

Este é um projeto de teste para desenvolvedores front-end React Pleno que visa avaliar suas habilidades na criação de aplicações web interativas e responsivas. A aplicação consome a API da Marvel para listar personagens icônicos do universo Marvel. Além disso, oferece a possibilidade de explorar detalhes dos personagens, incluindo informações sobre histórias em quadrinhos, eventos, séries e histórias em que eles apareceram.

## ✨ Recursos

A aplicação é composta por duas telas principais:

1.  **Tela de Pesquisa (Home):** Exiba uma lista de personagens da Marvel, mostrando suas imagens e nomes, com a possibilidade de páginar e buscar personagens pelo nome.

2.  **Tela de Detalhes:** Ao clicar em um personagem, você poderá ver informações detalhadas, como histórias em quadrinhos em que eles apareceram, eventos em que participaram, séries em que foram destaque e suas histórias e tudo páginado.

## 🛠️ Pré-requisitos

Antes de começar a usar o projeto 'marvel-v1', certifique-se de que você tenha os seguintes requisitos atendidos:

### Conhecimentos Necessários

- Familiaridade com desenvolvimento front-end e conceitos básicos de React.

- Compreensão de testes unitários e familiaridade com a estrutura de testes Jest.

### Estrutura do Projeto e Libs

#### Estrutura do Projeto

```
marvel-v1/
│
├─ src/
│ ├─ __tests__/ # Testes
│ ├─ assets/ # Imagens e ícones
│ ├─ components/ # Componentes reutilizáveis
│ ├─ contexts/ # Contextos reutilizáveis
│ ├─ hooks/ # Custom Hooks reutilizáveis
│ ├─ layout/ # Componentes de layout da aplicação
│ ├─ pages/ # Páginas da aplicação
│ ├─ types/ # Tipos de dados e interfaces
│ ├─ utils/ # Utilitários e funções auxiliares
│ │
│ ├─ app.tsx # Componente raiz da aplicação
│ ├─ main.tsx # Ponto de entrada da renderização
│
├─ README.md # Documentação do projeto
└─ package.json # Informações e dependências do projeto
```

#### Libs

Bibliotecas utilizadas e motivação:

- **md5:** O MD5 é uma ferramenta confiável para manter a integridade e a autenticidade dos dados, tornando-o essencial em muitos contextos de desenvolvimento e segurança de informações.
- **react-router-dom:** O uso do react-router-dom no React é essencial para criar aplicativos de página única (SPA) com navegação suave e dinâmica. Com suas rotas declarativas e capacidade de renderizar componentes específicos para cada URL, o react-router-dom simplifica a organização do aplicativo e oferece uma experiência de usuário mais fluida ao alternar entre diferentes páginas e estados. Além disso, ele integra-se perfeitamente com os recursos do React, permitindo criar interfaces de usuário interativas e responsivas de maneira eficiente.

## ⚙️ Instalação

- [Node.js - v18.17.1 ou superior](https://nodejs.org/): O projeto utiliza o Node.js para executar e construir a aplicação. Certifique-se de ter o Node.js instalado em sua máquina.

- [NPM - v9.6.7 ou superior](https://www.npmjs.com/): O gerenciador de pacotes Node.js é necessário para instalar e gerenciar as dependências do projeto.

Passo 1 - **Clone o repositório do projeto para sua máquina local usando o seguinte comando:**

```sh

https://github.com/rafalmeidas/marvel-v1.git

```

Passo 2 - **Ou [baixe](https://github.com/rafalmeidas/marvel-v1/archive/refs/heads/main.zip) o .zip e descompacte:**

Passo 3 - **Navegue para a pasta do projeto usando o terminal:**

```sh

cd marvel-v1

```

Passo 4 - **Instale as dependências do projeto usando NPM:**

```sh

npm install

```

Passo 5 - **Inicie a Aplicação:**

```sh

npm start

```

Pronto, basta acessar um navegador de sua preferência, e acessar o link a seguir:

- [🌐 marvel-v1](http://localhost:3000/)

Passo 6 - **Gerar Build de Deploy (Opcional):**

```sh

npm run build

```

## 🧪 Testar

Após efetuar o passo de [⚙️ Instalação](#instalação) execute o seguinte comando:

```sh

npm run test

```

## 📝 Licença

---

Feito com 💙 por Rafael.
