<img alt="Proffy" src="./.github/banner.png">

<p align="center"> 
  <img alt="Tamanho do Repositório" src="https://img.shields.io/github/repo-size/rafaelfachinelli/proffy-omnistack?style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rafaelfachinelli/proffy-omnistack?style=for-the-badge">
  <a href="https://github.com/rafaelfachinelli">
    <img alt="Feito pelo Rafael Fachinelli" src="https://img.shields.io/badge/feito%20por-Rafael Fachinelli-%237519C1?style=for-the-badge">
  </a>
  <img alt="Licença do Projeto" src="https://img.shields.io/github/license/rafaelfachinelli/Proffy?style=for-the-badge"/>
<p>

<p align="center">
 <a href="#computer-sobre">Sobre</a> •
 <a href="#memo-roteiro">Roteiro</a> •
 <a href="#triangular_ruler-status-do-projeto">Status</a> •
 <a href="#movie_camera-demonstração">Demonstração</a> •
 <a href="#dvd-executar-o-projeto">Executar</a> •
 <a href="#hammer-tecnologias">Tecnologias</a> •
 <a href="#boy-autor">Autor</a> •
 <a href="#page_facing_up-licença">Licença</a>
</p>

---
## :computer: Sobre

A plataforma é para estudantes e professores. Os professores realizam o cadastro inserindo as seguintes informações: Nome, biografia, whatsapp, disciplina e dias da semana com horários disponíveis para aula. Os alunos buscam professores particulares através do filtro de dia da semana, hora e matéria.

Projeto desenvolvido durante a **Next Level Week#2 (NLW)** na avançada **Trilha Omnistack** oferecida pela [Rocketseat](https://www.rocketseat.com.br).
O NLW é uma experiência online com muito conteúdo prático e desafios com duração de uma semana para conclusão.

---
## :memo: **Roteiro**

<div align="center">

|      Estado      |     Plataforma   |     Tarefa    |
|      :---:       |       :---:      |      :---     |
|:heavy_check_mark:|:computer:        |Estruturar página inicial|
|:heavy_check_mark:|:computer::iphone:|Estilizar página inicial|
|:heavy_check_mark:|:computer:        |Estruturar página de busca|
|:heavy_check_mark:|:computer::iphone:|Estilizar página de busca|
|:heavy_check_mark:|:computer:        |Configurações iniciais do servidor|
|:heavy_check_mark:|:computer:        |Estruturar rotas do servidor|
|:heavy_check_mark:|:computer:        |Estruturar página de cadastro|
|:heavy_check_mark:|:computer::iphone:|Estilizar página de cadastro|
|:heavy_check_mark:|:computer:        |Preparar cadastro de horários|
|:heavy_check_mark:|:computer:        |Carregar total de conexões na página inicial|
|:heavy_check_mark:|:computer:        |Funcionalidade de cadastrar novas aulas|
|:heavy_check_mark:|:computer:        |Listagem de professores na página de busca|
|:heavy_check_mark:|:computer:        |Criar projeto do aplicativo mobile com Expo|
|:heavy_check_mark:|:iphone:          |Estruturar página inicial do aplicativo|
|:heavy_check_mark:|:iphone:          |Estilizar página inicial do aplicativo|
|:heavy_check_mark:|:iphone:          |Navegação página inicial do aplicativo|
|:heavy_check_mark:|:iphone:          |Desenvolver navegação em stack do aplicativo|
|:heavy_check_mark:|:iphone:          |Estruturar página de dar aulas do aplicavo|
|:heavy_check_mark:|:iphone:          |Estilizar página de dar aulas do aplicavo|
|:heavy_check_mark:|:iphone:          |Desenvolver navegação de páginas internas do aplicavo|
|:heavy_check_mark:|:iphone:          |Desenvolver navegação em abas do aplicativo|
|:heavy_check_mark:|:iphone:          |Desenvolver componente header das páginas|
|:heavy_check_mark:|:iphone:          |Estruturar página de busca do aplicativo|
|:heavy_check_mark:|:iphone:          |Conexão da API|
|:heavy_check_mark:|:iphone:          |Listagem de professores|
|:heavy_check_mark:|:iphone:          |Filtro de professores|
|:heavy_check_mark:|:iphone:          |Lista de favoritos|
|:heavy_check_mark:|:iphone:          |Listagem de favoritos|
|:heavy_check_mark:|:iphone:          |Adição e remoção de favoritos|
|:heavy_check_mark:|:iphone:          |Listagem de professores|

</div>

---
## :triangular_ruler: **Status do Projeto**

<h4 align="center"> 
	👨‍🏫 Proffy v1.0 concluído !
</h4>

---
## :movie_camera: **Demonstração**

<p align="center"><b> :computer: WEB DESKTOP </b></p>

<p align="center"><kbd><img width="450" style="border-radius: 5px" height="250" alt="Demonstração do Aplicativo Proffy" src="./.github/demo-desk-study.gif"></kbd> <kbd><img width="450" style="border-radius: 5px" height="250" alt="Demonstração do Aplicativo Proffy" src="./.github/demo-desk-give-classes.gif"></kbd></p>

<p align="center"><b> :iphone: WEB MOBILE </b></p>

<div align="center">

Busca | Cadastro 
---|---
<img width="280" style="border-radius: 5px" height="450" alt="Demonstração do Aplicativo Proffy" src="./.github/demo-mobile-study.gif"> | <img width="280" style="border-radius: 5px" height="450" alt="Demonstração do Aplicativo Proffy" src="./.github/demo-mobile-give-classes.gif"> |

</div>

---
## :dvd: **Executar o Projeto**

### :desktop_computer: **WEB Responsivo**

Entre na pasta [`web/`](web/) e execute os seguintes comandos:

_com **npm**_

```bash
# Instalar dependências
$ npm install

# Iniciar servidor de desenvolvimento
$ npm start
```

_com **yarn**_

```bash
# Instalar dependências
$ yarn

# Iniciar servidor de desenvolvimento
$ yarn start

```

> O servidor de desenvolvimento iniciará na porta:3000 - Acesse <http://localhost:3000>

### :globe_with_meridians: **Servidor**

Entre na pasta [`server/`](server/) e execute os seguintes comandos:

_com **npm**_

```bash
# Instalar dependências
$ npm install

# Criar banco de dados
$ npm knex:migrate

# Iniciar servidor
$ npm start
```

_com **yarn**_

```bash
# Instalar dependências
$ yarn

# Criar banco de dados
$ yarn knex:migrate

# Iniciar servidor de desenvolvimento
$ yarn start
```

> O servidor iniciará na porta:3333 - Acesse <http://localhost:3333>

> O Banco de Dados fica salvo em [`src/database/database.sqlite`](src/database/database.sqlite)

### :iphone: **Aplicativo**

⚠️ No arquivo **api.ts** dentro da pasta [`mobile/src/services/`](mobile/src/services/) é necessário colocar o seu IP local na variável baseURL, mantendo a porta 3333 do servidor.

Entre na pasta [`mobile/`](mobile/) e execute os seguintes comandos:

_com **npm**_

```bash
# Instalar dependências
$ npm install

# Iniciar servidor de desenvolvimento
$ npm start
```

_com **yarn**_

```bash
# Instalar dependências
$ yarn

# Iniciar servidor de desenvolvimento
$ yarn start

```

> O expo para desenvolvimento iniciará na porta:19002 - Acesse <http://localhost:19002>

---
## :hammer: **Tecnologias**

As seguintes ferramentas foram utilizadas na construção do projeto:

<div align="center">

|WEB Responsivo								|Servidor					|Aplicativo|
|:---:									|:---:						|:---:|
|[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5)	|[Node.JS](https://nodejs.org/pt-br/)		|[Expo](https://expo.io)|
|[CSS3](https://developer.mozilla.org/pt-BR/docs/Archive/CSS3)		|[Express](https://expressjs.com/pt-br/)	|[React Native](https://reactnative.dev)|
|[Typescript](https://www.typescriptlang.org)				|[SQLite](https://www.sqlite.org/index.html)	|[Expo Google Fonts](https://github.com/expo/google-fonts)|
|[ReactJS](https://pt-br.reactjs.org)					|[KnexJS](http://knexjs.org)			|[React Navigation](https://reactnavigation.org)|
|									|[Axios](https://github.com/axios/axios)	||

</div>

---
## :boy: **Autor**

<a href="https://github.com/rafaelfachinelli">
 <img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/19878139?s=460&u=278a6f44f49af3c8edb13a811f7654dfe6e89341&v=4" width="100px;" alt="Foto de Perfil Rafael Fachinelli"/>
 <br />
 <sub><b>Rafael Fachinelli</b></sub></a> <a href="https://github.com/rafaelfachinelli" title="Rafael Fachinelli">💼</a>


Feito com ❤️ por Rafael Fachinelli 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Rafael_Fachinelli-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaelfachinelli/)](https://www.linkedin.com/in/rafaelfachinelli/)
[![Github Badge](https://img.shields.io/badge/-rafaelfachinelli-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/rafaelfachinelli)](https://github.com/rafaelfachinelli)
[![Itch.io Badge](https://img.shields.io/badge/-rafaelfachinelli-FA5C5C?style=flat-square&logo=itch.io&logoColor=white&link=https://rafael-fachinelli.itch.io/)](https://rafael-fachinelli.itch.io/)
[![Outlook Badge](https://img.shields.io/badge/-rafael.fachinelli@fatec.sp.gov.br-0078d4?style=flat-square&logo=microsoft-outlook&logoColor=white&link=mailto:rafael.fachinelli@fatec.sp.gov.br)](mailto:rafael.fachinelli@fatec.sp.gov.br)

---
## :page_facing_up: **Licença**

Copyright © 2020 [Rafael Fachinelli](https://github.com/rafaelfachinelli).<br />
Este projeto é licenciado pelo [MIT](./LICENSE).
