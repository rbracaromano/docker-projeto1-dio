# Servidor Apache HTTP com Docker

Este projeto configura um servidor Apache HTTP simples usando Docker. Ele serve uma página web básica. A configuração é feita através do arquivo `docker-compose.yml` e a página está localizada no diretório `website`.

## Pré-requisitos

- Docker instalado em sua máquina
- Docker Compose instalado

## Estrutura do Projeto

```bash
.
├── docker-compose.yml   # Configuração do Docker Compose
└── website              # Diretório para os arquivos da aplicação
    └── index.html       # Página HTML