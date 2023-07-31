# Simulador de Eleição #

Este é um programa em C que simula uma eleição com segundo turno utilizando o sistema de votação ranqueada. No sistema de votação ranqueada, os eleitores podem classificar os candidatos por ordem de preferência. O programa realiza o segundo turno até que um candidato alcance a maioria dos votos (mais de 50%). O código usa conceitos de manipulação de arrays, estruturas e lógica de programação para simular uma eleição com votação ranqueada.

## Como Executar o Programa ##

  1. Clone este repositório ou faça o download do arquivo runoff.c.
  2. Abra o terminal e navegue até o diretório onde o arquivo runoff.c está localizado.
  3. Compile o programa executando o seguinte comando no terminal:

    gcc -o runoff runoff.c

  4. Execute o programa com os nomes dos candidatos como argumentos, por exemplo:

    ./runoff Alice Bob Charlie

  5. Siga as instruções para cada eleitor, indicando suas preferências de voto (1º, 2º, 3º, etc.).
  6. O programa calculará o vencedor com base nas preferências dos eleitores e informará o resultado.
