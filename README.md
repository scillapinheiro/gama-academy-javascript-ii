<p align="center">
  <img src="https://github.com/scillapinheiro/gama_academy_desafio-1/blob/main/logo-gama-academy.png" width="50%">
</p>

<p align="center">
  <a href="#-Projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-executando-o-projeto">Executando o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="Grama XP 39" src="https://img.shields.io/static/v1?label=xp&message=39&color=success&labelColor=grey">
  
  <img alt="Stack Hacker" src="https://img.shields.io/static/v1?label=stack&message=hacker&color=success&labelColor=grey">
  
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=success&labelColor=grey">
</p>

## :computer: Projeto
Biblioteca simples de livros onde se é possível filtrar por categoria.

## :rocket: Tecnologias

Esse projeto foi desenvolvido com a seguinte tecnologia:

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## :arrow_forward: Executando o projeto
No CMD, inicie o projeto digitando:
```
npm start
```
Toda a lista de livros será carregada, seguida da pergunta:
```
Deseja buscar um livro? S/N
```
Se digitado ``S``, aparecerá as categorias disponíveis. Escolha uma e digite.
```
Essas são as categorias disponiveis:
Produtividade e estilo de vida /Historia brasileira /Americas /Estilo de vida /Tecnologia
Qual categoria você escolhe:
```
Se digitado ``N``, será exibida a lista completa de livros ordenada por número de paginas.
| (index) | (id) | nome | autor | categoria | paginas | recomenda| leu |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 0 | 6 | 'Padrões Javascript' | 'Stoyan Stefanov' | 'Tecnologia' | 231 | true | true |
| 1 | 6 | 'Digital Minimalism' | 'Cal Newport' | 'Produtividade e estilo de vida' | 254 | false | false |
| 2 | 1 | 'O Genocídio do negro brasileiro' | 'Abdias do Nascimento' | 'Historia brasileira' | 254 | false | false |
| 3 | 2 | 'As veias abertas da américa latina' | 'Eduardo galeano' | 'Americas' | 400 | false | false |
| 4 | 3 | 'Algoritmos para viver' | 'Brian Christian' | 'Tecnologia' | 412 | true | true |
| 5 | 4 | 'Thinking, fast and slow' | 'Daniel Kahneman' | 'Estilo de vida' | 418 | true | true |

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
