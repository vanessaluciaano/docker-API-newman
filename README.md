# Testes de Integração com Postman e Docker

Este repositório contém uma configuração do Docker Compose para executar testes de integração usando o Postman em uma API.

## Configuração do Ambiente

Certifique-se de ter o Docker e o Docker Compose instalados na sua máquina antes de executar os testes. Caso ainda não tenha, você pode instalá-los seguindo a documentação oficial do Docker.

## Executando os Testes

Siga as etapas abaixo para executar os testes de integração usando o Postman e o Docker:

1. Clone este repositório em sua máquina local
2. Navegue até o diretório clonado
3. Inicie os contêineres usando o Docker Compose
4. Execute o teste de integração 

## Estrutura do Projeto

- `docker-compose.yml`: Arquivo de configuração do Docker Compose, que define os serviços necessários para executar os testes de integração.
- `Fruits.postman_collection.json`: Coleção do Postman contendo os testes de integração da API.
- `QA.postman_environment.json`: Arquivo de ambiente do Postman contendo as variáveis de ambiente para os testes.
- `report/`: Diretório onde o relatório HTML gerado pelo teste será armazenado.
- `report/template.hbs`: Modelo do relatório HTML personalizado.
