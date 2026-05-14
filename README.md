# MCA Bank Marketing — UCI Dataset

Projeto de **Análise de Correspondência Múltipla (MCA)** usando o dataset **Bank Marketing**, da UCI Machine Learning Repository.

A base tem 45.211 registros e está relacionada a campanhas de marketing direto de uma instituição bancária portuguesa. A página da UCI informa que as campanhas foram baseadas em contatos telefônicos e que o objetivo original era analisar se o cliente assinaria ou não um depósito a prazo.

## Objetivo

Aplicar MCA para transformar variáveis categóricas em coordenadas numéricas e visualizar associações entre categorias em um mapa perceptual.

## Dataset

Fonte: UCI Machine Learning Repository — Bank Marketing Dataset  
Tema: campanhas de marketing direto de uma instituição bancária portuguesa.

O notebook baixa automaticamente o arquivo `bank.zip` da UCI e utiliza o arquivo `bank-full.csv`.

## Principais etapas

1. Leitura do dataset da web
2. Preparação das variáveis categóricas
3. Criação de faixas para variáveis numéricas
4. Testes qui-quadrado exploratórios
5. Ajuste da MCA
6. Análise de autovalores e inércia
7. Extração das coordenadas das categorias
8. Construção do mapa perceptual
9. Interpretação das proximidades entre categorias

## Técnica

- Multiple Correspondence Analysis (MCA)
- Análise exploratória não supervisionada
- Visualização de associações entre categorias

## Observação

A MCA não é usada aqui como modelo preditivo supervisionado. A variável `assinou_deposito` é tratada apenas como mais uma categoria para análise exploratória.
