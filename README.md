# Desafios

## Desafio 01 (Conversão de Números Romanos)

- Linguagem utilizada: Python
- Conversor de numeros romanos para o seu valor em inteiro
- Input do usuário: Numero romano

```
input_ = "MLVIII"
```

- Output do código:

```
O numero romano MLVIII em inteiro é 1058
```
---

## Desafio 02 (Desafio das Constelações)

- Linguagem utilizada javascript + HTML
- Um codigo para criar uma matriz de adjacencia de uma constelação de estrelas (minimo 4 , maximo 8) e checar se 2 estrelas estão diretamente interligadas
- Uma estrela "i" está ligada a uma "j" se M[i][j] = 1
- Input do usuário: Tamanho da matriz para ser criada, estrelas a serem comparadas (utilização do Window prompt)
- Exemplo de output:

![alt text](https://github.com/paulo7676/Desafios/blob/master/Output_D2.png)
---

## Desafio 03 (Poker Espacial)

- Linguagem utilizada: Python
- Um codigo para simular um jogo de poker entre 2 jogadores,seguindo a hierarquia padrão do jogo mas ignorando desempates em combinações de cartas.
- Utilizado bibliotecas nativas do python random e itertools para embaralhar o baralho e realizar uma combinação simples das cartas do usuario e da mesa
- Utilização das funções map() para retornar o melhor valor de todas as combinações e a função filter() para obter esse melhor valor para a mão

```
import random 
from itertools import combinations 
```

- Input do usuário: Não é necessário
- Output: é retornado as cartas da mesa e de cada robô, junto com a melhor combinação entre elas e qual robô ganhou ou se ouve empate
- Exemplos de Output:

```
Cartas na mesa: ['7C', '3E', 'AC', '10E', 'AP']
Mão Robo1: ['AE', 'KO']
Mão Robo2: ['9C', '6C']
Melhor combinação robo 1: ('AE', 'KO', '7C', 'AC', 'AP') trio.
Melhor combinação robo 2: ('9C', '6C', '7C', 'AC', 'AP') par.
Robo 1 ganhou
```
```
Cartas na mesa: ['JC', 'AC', '7O', '10E', '3O']
Mão Robo1: ['9P', '9E']
Mão Robo2: ['JO', '6C']
Melhor combinação robo 1: ('9P', '9E', 'JC', 'AC', '7O') par.
Melhor combinação robo 2: ('JO', '6C', 'JC', 'AC', '7O') par.
Empate
```
```
Cartas na mesa: ['6P', '10P', 'JC', '5P', 'KE']
Mão Robo1: ['AC', '8P']
Mão Robo2: ['7O', '2O']
Robo 1 ganhou com a carta alta: AC
```
