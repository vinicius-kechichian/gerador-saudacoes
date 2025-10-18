# Gerador de Saudações

Projeto de microserviços Dockerizados que gera saudações aleatórias combinando pessoas e frases.

## Estrutura do Projeto

- `ms-pessoas-aleatorias/`: microserviço responsável por retornar nomes aleatórios de pessoas.
- `ms-saudacoes-aleatorias/`: microserviço responsável por retornar saudações aleatórias.
- `site-gerador-saudacoes/`: frontend web para interação com os microserviços.
- `docker-compose.yaml`: orquestração dos containers com Docker Compose.

## Como rodar

Certifique-se de ter o Docker e Docker Compose instalados.

No diretório raiz do projeto, execute:

```bash
sudo docker compose up -d

