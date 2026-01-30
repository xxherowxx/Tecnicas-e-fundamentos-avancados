# Desenvolvimento do Jogo Super Trunfo em Linguagem C
## Fundamentos e Técnicas Básicas

---

## 1. Introdução
O Super Trunfo é um jogo de cartas bastante conhecido, no qual os jogadores comparam atributos de suas cartas para determinar o vencedor da rodada. Por sua simplicidade lógica e regras bem definidas, o jogo se torna um excelente estudo de caso para a aplicação dos fundamentos da programação em linguagem C.

Este trabalho tem como objetivo apresentar os conceitos básicos necessários para desenvolver a lógica do jogo Super Trunfo utilizando a linguagem C, abordando fundamentos e algumas técnicas introdutórias, sem aprofundamento excessivo em algoritmos avançados.

---

## 2. Visão Geral do Jogo Super Trunfo
No Super Trunfo, cada carta possui um conjunto de atributos numéricos (como força, velocidade, peso, entre outros). Em cada rodada, um jogador escolhe um atributo, e o valor desse atributo é comparado entre as cartas dos jogadores. A carta com o maior valor vence a rodada.

Características principais do jogo:
- Comparação de valores numéricos
- Regras simples
- Fluxo repetitivo de rodadas
- Definição clara de vencedor

---

## 3. Fundamentos da Linguagem C Aplicados

### 3.1 Entrada e Saída de Dados
A linguagem C utiliza funções como `printf` e `scanf` para interação com o usuário. No Super Trunfo, essas funções são usadas para:
- Mostrar informações das cartas
- Receber a escolha do atributo

---

### 3.2 Variáveis e Tipos de Dados
O jogo utiliza tipos básicos da linguagem C, como:
- `int` para atributos numéricos
- `char` para nomes e identificadores

Esses tipos permitem armazenar e comparar os dados das cartas.

---

### 3.3 Estruturas de Decisão
Estruturas condicionais como `if`, `else if` e `else` são utilizadas para:
- Comparar atributos das cartas
- Definir o vencedor da rodada

---

## 4. Estruturas de Dados Simples

### 4.1 Uso de Struct
Uma `struct` é utilizada para representar uma carta do jogo, agrupando seus atributos em uma única estrutura. Isso torna o código mais organizado e fácil de entender.

---

## 5. Fluxo Básico do Jogo
O funcionamento lógico do jogo pode ser descrito pelas seguintes etapas:

1. Definição das cartas
2. Exibição dos atributos
3. Escolha do atributo pelo jogador
4. Comparação dos valores
5. Declaração do vencedor da rodada

Esse fluxo pode se repetir ao longo do jogo.

---

## 6. Técnicas Básicas Utilizadas

### 6.1 Estruturas de Repetição
Laços como `for` e `while` permitem repetir rodadas do jogo sem a necessidade de duplicar código.

### 6.2 Organização do Código
A separação do código em funções facilita a leitura e a manutenção do programa.

---

## 7. Limitações e Possíveis Melhorias
Por se tratar de uma abordagem básica, o projeto apresenta algumas limitações, como:
- Número reduzido de cartas
- Comparação simples entre dois jogadores

Como melhorias futuras, podem ser implementados:
- Maior quantidade de cartas
- Modo multiplayer
- Interface gráfica

---

## 8. Importância para Estudantes de ADS
O desenvolvimento do Super Trunfo em C auxilia o estudante a compreender:
- Lógica de programação
- Estruturas básicas da linguagem C
- Organização de algoritmos simples

---

## 9. Conclusão
O jogo Super Trunfo, quando desenvolvido em linguagem C, mostra-se uma excelente ferramenta para a aplicação prática dos fundamentos da programação. Mesmo com uma implementação básica, o projeto contribui significativamente para a formação de estudantes de Análise e Desenvolvimento de Sistemas.

---

## 10. Referências
- Documentação oficial da linguagem C
- Material didático de Lógica de Programação
- Conteúdos introdutórios sobre desenvolvimento de jogos
