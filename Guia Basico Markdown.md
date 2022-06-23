# Comandos em Markdown
Comandos basicos em Markdown

------------------------------------------

# TITULO = Uma hashtag no inicio (com espaço entre ela e o texto)
## TITULO 2 = Duas hastags no inicio (com espaço entre ela e o texto)
### TITULO 3 = Tres hashtags no inicio (com espaço entre ela e o texto)

*Italico* = O termo entre um astericos

**Negrito** = O termo entre dois asterisco

__*Negrito e Italico*__ = O termo entre dois underlines e um asterisco


----------------------------------------------

Lista Numerada (Feito colocando um numero, seguido de um ponto e espaço. Subitens são feitos dando tres espaços antes do numero e do ponto)
1. Teste
2. Teste2
3. Teste3
   1. Subteste1 de Teste3
   2. Subteste2 de Teste3


Lista Demarcada (Feito colocando um asterisco, dando espaço e escrevendo o testo desejado. Subitens são feitos com os tres espaços antes do asterisco)
* Teste
* Teste
* Teste
   * Teste
   * Teste
* Teste

Lista de Tarefas (Feito com sinal de menos, dando espaço, abrindo e fechando colchetes [] com um espaço entre eles. Colocando um X entre os colchetes no lugar do espaço vazio, é criado uma tarefa já concluida)
- [ ] Tarefa 1
- [ ] Tarefa 2
- [ ] Tarefa 3
- [x] Tarefa Concluida


------------------------------------------------------

Embutir Links = Coloque o texto que vai receber o link entre colchetes seguido do link entre parenteses. Ex: [aqui vai o texto](aqui o link).

[Acesse o meu Github](https://github.com/thuliopereira/)

-------------------------------------------------------

Criar tabelas

Feita criando primeiro as colunas, colocando o nome de cada coluna separada da outra por um espaço + PIPE + espaço. Ex: Numero | Nome | Nota
Em seguida, na linha de baixo, colocamos tres simbolos de menos para cada coluna criada na linha anterior, tambem separadas pelo kit de espaço + PIPE + Espaço. No caso desse exemplo, teremos tres conjuntos de simbolos de menos e dois PIPES. Ex: --- | --- | ---
Nas linhas seguintes vamos criar cada elemento, separando a informação que sera atribuida a cada coluna dividida pelo kit de espaço + PIPE + espaço. Ex: 1 | Aluno A | 8.0

Numero | Nome | Nota
--- | --- | ---
1 | Aluno A | 8.0
2 | Aluno B | 5.0
3 | Aluno C | 9.5

----------------------------------------------------------

Citação de comandos e codigos

Colocando um comando (ou trecho) entre duas crases, podemos destaca-lo com fonte e fundo diferentes
`variavel.getvalue();`

-----------------------------------------------------------

Citação de trechos de codigos

Usando trechos de codigos entre tres crases, tambem vamos destacar o trecho
```
nota = teclado.nextint();
if(nota > 5){
    System.out.print("Aluno APROVADO");
}else{
     System.out.print("Aluno Reprovado");
     }
``` 

------------------------------------------------------------

Emoticons

Podemos usar emoticons, colocando o codigo dele entre dois pontos, como exemplo

:Hand: ✋ (o codigo dos emoticons deve ser todo em minusculo, foi citado em maiusculo para demonstrar o uso)

