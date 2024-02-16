# VidFlow

O VidFlow é uma plataforma de compartilhamento de vídeos.

## Índice

- [Design do Projeto](#design-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Rodar o projeto localmente](#rodar-o-projeto)

## Design do Projeto

Visão mobile  
![Captura de tela do vidflow](./vidflow-mobileview.png)  
Visão desktop  
![Captura de tela do vidflow.](./vidflow.png)

## Tecnologias Utilizadas

- Node.js
- NPM
- Os pacotes ESLint, JSON Server, Axios e Vite
- HTML, CSS e JavaScript

## Rodar o projeto

Após baixar ou clonar o projeto deste repositório, você precisa ter o [Node.js](https://nodejs.org/) instalado.

execute o commando

```bash
npm install 
```
para instalar todas as dependências do projeto

em seguida

````bash
npm run dev
````

Caso queira editar o projeto, e talvez alterar a "API", troque a URL que está no parâmetro do método _get_ do _Axios_ por "http://localhost:3000/videos" e execute o ````npm run dev```` normalmente em seguida

```bash
npm run api-local
```
