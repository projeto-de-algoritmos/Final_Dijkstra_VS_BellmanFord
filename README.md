# Trajeto Dijkstra Vs Bellman-Ford

**Número da Lista**: X<br>
**Conteúdo da Disciplina**: Final<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 18/0096991  |  Álvaro Leles Guimaraes |
| 18/0102087  |  Ian Fillipe Pontes Ferreira |

## Sobre 
Descreva os objetivos do seu projeto e como ele funciona. 

## Screenshots

<div align="center">

Posição inicial do táxi | Táxi pegando o passageiro | Táxi deixando o passageiro
:---------: | :------: | :-------:
![imagem](assets/inicio.png) | ![imagem](assets/meio.png) | ![imagem](assets/fim.png)
| Dijkstra | | Bellman-Ford
| ![imagem](assets/dijkstra.gif) | | ![imagem](assets/bellman_ford.gif)

</div>

<div align="center">
Tabela 1: Screenshots do projeto e um gif que mostra o programa rodando
</div>

## Instalação 
**Linguagem**: Python<br>
**Pré-requisitos**: Para rodar o projeto é necessário ter o Python instalado na versão 3.6.8, que foi a versão utilizada, ou uma versão superior. Acesse <a href="https://www.python.org" target="_blank">aqui</a> para instalar o Python.

## Uso 
Explique como usar seu projeto caso haja algum passo a passo após o comando de execução.

## Outros 

<div align="center">

![imagem](assets/taxienv.png)

[Figura 1: Representação do mapa](./assets/taxienv.png)

</div>

No mapa, o passageiro sempre será representado pelo cor rosa, e o destino pela cor azul. Sendo que, tanto o passageiro quanto o destino, podem estar em 4 possíveis localizações.

- Possíveis localizações do passageiro e do destino:

<div align="center">

|Index|Letra
|:---:|:---:|
|  0 | R  |   
| 1  | G  |   
| 2  | Y  |  
| 3  | B  | 
</div>

<div align="center">
Tabela 2: Índices que mostram as possíveis posições de origem e destino do passageiro
</div>

