#  FLS 6397 - Introdução à Programação e Ferramentas Computacionais para as Ciências Sociais

- Responsáveis: Leonardo S. Barone e Jonathan Phillips

# Desafio 1

## Instruções para Entrega

Data: 20/04

Formato: RScript (arquivo .R)

Via: e-mail com título "[FLS6397] - D1" para leobarone@gmail.com e jonnyphillips@gmail.com.

## Instruções para a atividade

Siga as instruções abaixo. Documente __TODOS__ os seus passos em um script. Comente no seu script __TODOS__ os seus passos e explique a si mesma(o) suas escolhas e estratégias. Colar pedaços de código de outras(os) colegas nesta atividade é permitido e peça ajuda se precisar. Mencione __SEMPRE__ em comentários quando a solução encontrada não for sua.

As primeiras linhas do seu script devem conter suas informações pessoais como comentário, tal qual o modelo abaixo:

```{r}
### nome <- "Fulano da Silva Sauro"
### programa <- "Mestrado em Paleontologia"
### n_usp <- 32165498
### data_entrega: "29/02/2017"
```

## Roteiro da atividade

1- Vá ao [Repositório de Dados Eleitorais do TSE](http://www.tse.jus.br/eleitor-e-eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais). Na página "Resultados" e no ano 2016, faça o download do arquivo "Votação nominal por município e zona" e descompacte-o. Você pode fazer tudo à mão se tiver dificuldade de copiar o modelo do [tutorial 4](https://github.com/leobarone/FLS6397_2018/blob/master/tutorials/tutorial04.Rmd), em que abrimos os dados da MUNIC 2005. 

2- Importe para o R os resultados eleitorais dos 3 estados do Sul.

3- Com a função _rbind_, junte os 3 _data frames_ importados.

4- Leia até o final as instruções e identifique quais variáveis são necessárias para tarefa. Selecione apenas tais variáveis e renomeia-as (você pode trocar a ordem se achar mais fácil).

5- Selecione apenas as linhas que contém resultados eleitorais para prefeita(o).

6- Selecione apenas as linhas que contém os resultados eleitorais para prefeitas(os) eleitas(os).

7- Quantas linhas restaram? Quantas colunas? (postarei o gabarito ao longo da semana no repositório).

8- Crie, a seu critério, 3 categorias de partido e crie uma nova variável: esquerda, direita, outros partidos. Dê o nome de partido\_categoria a esta variável.

9- Faça uma tabela da nova variável.
