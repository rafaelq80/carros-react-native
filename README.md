<h1>Desafio de projeto - Lamborghini Showcase</h1>

<br />

<div align="center">
    <img src="https://i.imgur.com/EGUUELt.png" title="source: imgur.com" width="60%"/> 
    <p>+</p>
    <img src="https://ik.imagekit.io/vzr6ryejm/react_native/logo-wordmark-light_v2.png?updatedAt=1719817353728" title="source: imgur.com" width="25%"/> 
</div>


<br />

<div align="center">
  <img src="https://img.shields.io/github/languages/top/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/github/repo-size/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/github/issues/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/github/issues-pr/rafaelq80/portfolio-react-native?style=flat-square" />
  <img src="https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen" alt="Status: Concluído">
</div>

<br />

Aplicativo desenvolvido com **React Native** e **Expo**, que exibe uma coleção de carros da marca **Lamborghini**, consumindo dados de uma **API fake**. O app apresenta imagens, detalhes e preços dos modelos, com uma interface moderna e navegação fluida.

<br />

## 🔐 Funcionalidades

- ✅ Listagem de carros Lamborghini
- 🔍 Visualização de detalhes de cada modelo
- 🖼️ Exibição de imagens e preços
- 🧭 Navegação entre telas
- 🛒 Botão de compra ilustrativo (“Buy This”)

<br />

## 🗂️ Estrutura do Projeto

```
.
├── App.tsx
├── index.ts
├── package.json
├── tsconfig.json
├── app.json
├── assets/
└── src/
    ├── api/         # Funções para chamadas HTTP
    ├── components/  # Componentes reutilizáveis
    ├── constants/   # Constantes globais (cores, textos, etc.)
    └── screens/     # Telas da aplicação
```

<br />

## 📦 Tecnologias Utilizadas

| Tecnologia                               | Descrição                                                    |
| ---------------------------------------- | ------------------------------------------------------------ |
| [React Native](https://reactnative.dev/) | Framework para desenvolvimento mobile multiplataforma        |
| [Expo](https://expo.dev/)                | Plataforma que facilita o desenvolvimento e execução de apps React Native |
| [Axios](https://axios-http.com/)         | Cliente HTTP para chamadas à API                             |

<br />

## ⚙️ Pré-requisitos

- [Node.js](https://nodejs.org/) (v16 ou superior)
- npm

<br />

## 🛠️ Instalação e Configuração

### Instalação do Expo

```bash
npm install expo-cli@latest
```

### Clonando o repositório

```bash
git clone https://github.com/rafaelq80/portfolio-react-native
cd portfolio-react-native
```

### Instalando as dependências

Utilize o comando abaixo para instalar todas as bibliotecas através do npx:

```bash
npx expo install
```

<br />

## ▶️ Executando o Projeto

| Comando           | Descrição                         |
| ----------------- | --------------------------------- |
| `npm start`       | Inicia o projeto com o Expo       |
| `npm run android` | Executa o app no emulador Android |
| `npm run ios`     | Executa o app no emulador iOS     |
| `npm run web`     | Executa o app no navegador (web)  |

📱 Abra o app no Emulador de sua preferência ou no seu celular (Android ou IOS), apontando para o QR-Code que será exibido no Terminal

> [!TIP]
>
> Para executar o app no seu celular, visite a loja de aplicativos do seu aparelho e instale o **Expo Go**.

> [!WARNING]
>
> No Ambiente Windows, só é possível gerar o app na versão Android. Para gerar o app na versão IOS é necessário utilizar uma máquina virtual ou um computador da Apple executando o MAC OS.

<br />

## 🌐 API Utilizada

Os dados dos carros são obtidos a partir da seguinte URL pública:

```
https://digitalinnovationone.github.io/fake-data-api-lamborghini/api/lamborghini.json
```

> Esta API fornece dados fictícios de carros da Lamborghini, incluindo nome, imagem e preço.

<br />

## 📸 Capturas de Tela 

<div align="center">
    <img src="https://i.imgur.com/TINBhlp.png" title="source: imgur.com" width="40%"/> 
</div>

<br />

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/NovaFeature`)
3. Commit suas alterações (`git commit -m 'feat: adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

<br />

## 📄 Licença

Este projeto é apenas para fins educacionais e demonstrativos. Lamborghini é uma marca registrada do Grupo Volkswagen

<br />

⭐Se este projeto foi útil para você, não esqueça de deixar uma estrela!