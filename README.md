# Teste para test-developers em Rails
Este teste é apresentado aos candidatos as vagas de desenvolvimento de testes em Rails para avaliar os quesitos técnicos.

## Desafio e objetivo

Seu objetivo é, através do projeto contido neste repositório desenvolver suites de testes para verificar alguns comportamentos listados abaixo. Os testes podem ser desenvolvidos utilizando quaisquer bibliotecas ou frameworks disponíveis em Rails, mas preferencialmente damos muito valor a gem [Minitest](https://github.com/blowmage/minitest-rails) e recomendamos o uso da gem [FactoryBot](https://github.com/thoughtbot/factory_bot_rails) para criação das instâncias de objetos a serem usados nos estes.

## Sobre o projeto
Uma rede de bancos mundialmente famoso chamada Cris&Financeira quer desenvolver um sistema para gerenciamento tanto de seus inúmeros bancos quanto de seus respectivos clientes. O sistema conta com 3 entidades básicas:

- Cliente
- Banco
- Conta bancária
- Transaferência (superclasse)
-- Deposito (classe filha de transferência)
-- Retirada (classe filha de transferência)

As classes podem ser inspecionadas no diretório **app/models**.


## Critérios que serão avaliados

- Organização dos casos de teste
- Legibilidade do código escrito
- Reaproveitamento e reuso de código
- Tempo para finalização do teste
- Expertise demonstrada nas perguntas dissertativas
- Taxa de assertividade nos casos de teste com base no gabarito
- Escrita dos testes em **inglês**

