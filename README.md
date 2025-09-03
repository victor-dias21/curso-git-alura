# Projeto do Curso Git e GitHub: Compartilhando e Colaborando em Projetos (Alura)
https://alura.com.br/course/git-github-compartilhando-colaborando-projetos

<h1>Jogo do número secreto</h1>

<h2> Sobre</h2>
<p>Projeto utilizado no Curso Git e GitHub: Compartilhando e Colaborando em Projetos da Alura.</p>
<p>PS* utilizei alguns conceitos de Docker para relembrar um aprendizado recente</p>
## Tecnologias
<div>
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</div>

// Código omitido. 


Este projeto foi desenvolvido como parte do curso [Git e GitHub: compartilhando e colaborando em projetos](https://alura.com.br/course/git-github-compartilhando-colaborando-projetos) da Alura. O objetivo é praticar os principais conceitos e comandos do Git, além de aprender como colaborar em projetos utilizando o GitHub.

## Sobre o Projeto

O projeto simula um fluxo de trabalho real com versionamento de código, colaboração entre desenvolvedores e uso de repositórios remotos. Durante o curso, foram abordados temas como:

- **Versionamento de código:** Controle de versões para acompanhar o histórico de alterações.
- **Branches:** Criação e gerenciamento de ramificações para desenvolvimento paralelo.
- **Merge:** Integração de mudanças entre branches.
- **Resolução de conflitos:** Como lidar com conflitos durante o merge.
- **Repositórios remotos:** Uso do GitHub para hospedagem e colaboração.
- **Pull Requests:** Proposta de alterações e revisão de código.
- **Forks e clones:** Como contribuir em projetos de terceiros.

## Principais Comandos Git Aprendidos

- `git init` — Inicializa um novo repositório Git.
- `git clone` — Clona um repositório remoto.
- `git status` — Exibe o estado atual do repositório.
- `git add` — Adiciona arquivos à área de stage.
- `git commit` — Salva alterações no histórico do repositório.
- `git push` — Envia alterações para o repositório remoto.
- `git pull` — Atualiza o repositório local com as alterações remotas.
- `git branch` — Gerencia branches.
- `git merge` — Mescla branches.
- `git log` — Visualiza o histórico de commits.

## Como Executar

1. Clone o repositório:
   ```
   git clone <url-do-repositorio>
   ```
2. Navegue até a pasta do projeto:
   ```
   cd docker
   ```
3. Construa a imagem Docker:
   ```
   docker build -t meu-site .
   ```
4. Execute o container:
   ```
   docker run -d -p 80:80 --name site meu-site
   ```
5. Acesse no navegador:
   ```
   [cd docker](http://localhost)
   ```


---

Este projeto é uma ótima oportunidade para consolidar o aprendizado sobre Git e GitHub, facilitando o trabalho colaborativo e o controle de versões em projetos de desenvolvimento de software.
