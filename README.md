# ABB
Implementação de uma Árvore Binária de Busca em java com alguns métodos interessantes: encontrar o n-ésimo elemento, achar aposição de um elemento, obter a mediana da ABB, verificar se ela é cheia, e gerar uma String pela sequencia de visitação por nível.
## Pré-requisitos
Caso você não tenha o java instalado no seu computador, digite o comando no terminal ```sudo apt-get install openjdk-7-jdk```.
Para verificar se você já possui, basta digitar ```java -version``` 
## Como compilar
```:~/ABB$ javac *.java```
## Como executar
```:~/ABB$ java Principal```
## Construção da Árvore
Para construir a árvore, salve no arquivo "arvore.txt" uma sequência de números inteiros separados apenas por 01 (um) espaço. O arquivo já têm um exemplo, basta sobrescrevê-lo com os valores desejados.
## Sequênca de operações
No arquivo "operacoes.txt" digite as operações que desejas executar, linha por linha. Caso ela possua algum argumento, digite-o logo após o comando com 01 (um) espaço.
### Exemplo
IMPRIMA

MEDIANA

ENESIMO 10
### Guia das operações
- ENESIMO N: retorna o n-ésimo elemento (contando a partir de 1) do percurso em ordem (ordem simétrica) da ABB.
- POSICAO N: retorna a posição ocupada pelo elemento x em um percurso em ordem simétrica na ABB (contando a partir de 1).
- MEDIANA:  retorna o elemento que contém a mediana da ABB. Se a ABB possuir um número par de elementos, retorne o menor dentre os dois elementos medianos.
- CHEIA: retorna verdadeiro se a ABB for uma árvore binária cheia e falso, caso contrário.
- COMPLETA:  retorna verdadeiro se a ABB for uma árvore binária completa.
- IMPRIMA: retorna uma String que contém a sequência de visitação (percorrimento) da ABB por nível.
- REMOVA N: remove o elemento N da ABB, se ele não estiver, não faz nada.
- INSIRA N: insere o elemento N na ABB, se ele já estiver, não faz nada.


