<h1 align="center">Tipos Primitivos Numéricos</h1>

<p>Hoje vamos conhecer os tipos primitivos númericos do Java.</p>

<ul>
//Dados numéricos inteiros<br>
<strong>byte:</strong>  É o tipo de dado capaz de armazenar 8 bits de informação, ou seja, um número inteiro entre -128 e 127. Sua utilização é recomendada em caso de economia de memória, já que alguns tipos de dados maiores possuem processamento mais rápido;<br>
<br>
<strong>short:</strong> É o tipo de dado que é capaz de armazenar números inteiros de 16 bits, ou seja, um número inteiro entre -32.768 e 32.767;<br>
<br>
<strong>int:</strong> É o tipo de dado capaz de armazenar 32 bits, ou seja, de representar um número inteiro qualquer entre -2.147.483.648 e 2.147.483.647. É o tipo mais indicado na maioria dos casos por possuir uma grande faixa de valores. Variáveis deste tipo também costumam ser manipuladas mais rapidamente já que correspondem à largura de dados (de palavra) mais usual na maioria dos processadores atuais; <br>
<br>
<strong>long:</strong> É o tipo de dado capaz de armazenar 64 bits de informação, ou seja, que pode representar um número inteiro qualquer entre -9.223.372.036.854.775.808L e 9.223.372.036.854.775.807L. Recomenda-se seu uso apenas quando for preciso assumir valores maiores ou menores do que aqueles possíveis de serem assumidos pelo int; <br>
<br>
//Dados numéricos reais<br>
<strong>float:</strong> É o tipo de dado capaz de armazenar números reais de precisão simples, ou seja, 32 bits de informação representando um número real; <br>
<br>
<strong>double:</strong> É o tipo de dado capaz de armazenar números reais de precisão dupla, ou seja, 64 bits de informação em forma de número real. É usado para representar valores nos quais é preciso uma precisão maior que a de float;<br>
</ul>

<p>Vamos colocar isso em prática. Abra o IntelliJ, crie uma nova classe Java e teste cada dado com uma numeração diferente. Após isso, imprima o resultado.</p>
<p>Aqui está um exemplo de como você pode fazer:</p>
<blockquote>
public class TiposPrimitivosNumericos {<br>
    public static void main(String[] args) {<br>
        byte a = 1;<br>
        short b = 11;<br>
        int c = 111;<br>
        long d = 1111;<br>
        float e = 11111;<br>
        double f = 1.1111;<br>
        System.out.println(a);<br>
        System.out.println(b);<br>
        System.out.println(c);<br>
        System.out.println(d);<br>
        System.out.println(e);<br>
        System.out.println(f);<br>
    }<br>
}<br>
</blockquote>

<p>O que acontece se eu coloco um valor superior ao permitido? O programa nem compila, ele aponta o erro na hora. Tente alterar o byte para 128 e faça o teste.</p>
<p>Ele deu erro, certo? Ele aceita apenas até o valor 127, acima disso ele acusa o seguinte erro:</p>
<blockquote>
java: incompatible types: possible lossy conversion from int to byte
</blockquote>
<p>O programa pede para que você altere o <i>byte</i> para <i>int</i> para que o valor seja aceito. Da mesma forma o <i>int</i> só vai aceitar o valor até 2.147.483.647, onde após isso ele acusará um erro e solicitará que seja alterado para <i>long</i>.</p>

<p1><strong>Conteúdo Extra</strong></p1>
<p>Vamos aproveitar que você está com o programa aberto e fazer um cálculo bem simples utilizando o <i>int</i>. Escrava o seguinte no programa:</p>
<blockquote>
int x = 10;<br>
int y = 20;<br>
int z = 12;<br>
</blockquote>
<p>Agora imprima x+y-z. <strong>Lembre-se que neste caso você não vai colocar aspas dentro dos parênteses do println</strong>. Qual foi o resultado impresso?</p>
<p>Agora altere o <i>int z</i> para <strong>int z = x + y;</strong> e imprima apenas z. Qual foi o resultado?</p>
<p>Você pode brincar fazendo cálculos a vontade, onde:</p>
<ul>
<strong>+</strong> soma<br>
<strong>-</strong> diminui<br>
<strong>*</strong> multiplica<br>
<strong>/</strong> divide<br>
</ul>

<p>Divirta-se! Em breve vamos fazer uma calculadora juntos!</p>
