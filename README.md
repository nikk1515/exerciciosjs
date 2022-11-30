# exerciciosjs
são 7 exercícios ao todo
1 calcular média
<html>
<head>
</head>
<title>media</title>
<body>
<script>
var n1, n2, n3, n4, n5;
 n1 = prompt("digite a nota: ")
 m1 = eval (n1)
 n2 = prompt ("digite a segunda nota: ")
 n2 = eval (n2)
 n3 = prompt ("digite a terceira nota: ")
 n3 = eval (n3)
 n4 = prompt ("digite a quarta nota: ")
 n4 = eval (n4)
 n5 = prompt ("digite a quinta nota: ")
 var media = (n1, n2 , n3 , n4, n5 / 5)
alert ("a media e : " + media)
</script>
</body>
</html>
2 imprimir o quadrado de cada número
<html>
<head></head>
<title>quadrado</title>
<body>
<script>
var R = prompt("digite um numero: ")
R = (Math.sqrt(R))
alert("a raiz quadrada e: " + R)
</script>
</body>
</html>
3 descobrir qual o maior número
<html>
    <head>
        <title>Exercicio 3</title>

        <script type="text/javascript">

            
            var n1 = 1000
            var n2 = 2
            var n3 = 5

            var maior = n1;

            if(n2 > maior)
             maior = n2;
             if(n3 > maior)
              maior = n3;

              alert("Maior: " + maior);
        </script>
    </head>
</html>


4 quantas pessoas são maiores de idade
<html>
    <head>
        <title>Exercicio 3</title>

        <script type="text/javascript">

            
            var n1 = 1000
            var n2 = 2
            var n3 = 5

            var maior = n1;

            if(n2 > maior)
             maior = n2;
             if(n3 > maior)
              maior = n3;

              alert("Maior: " + maior);
        </script>
    </head>
</html>

5 dados de altura e sexo
<html>
    <head>
        <title>Exercicio 3</title>

        <script type="text/javascript">

            
            var n1 = 1000
            var n2 = 2
            var n3 = 5

            var maior = n1;

            if(n2 > maior)
             maior = n2;
             if(n3 > maior)
              maior = n3;

              alert("Maior: " + maior);
        </script>
    </head>
</html>

6 nomes de maneira invertida
<!DOCTYPE html>
<html>
<head>
<title>nomes</title>
<meta charset="UTF-8>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script>
{
 var nomes = prompt("digite alguns nomes")
 nomes = nomes.split(",");

 for(i=nomes.length-1;i>=0;i--){
alert(nomes[i]);


 }

}
</script>
</head>
<body>
    
</body>
</html>



7 exibir data
<!DOCTYPE html>
<html>
<head>
    
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>data</title>
    </head>
    <body>
        
    </body>
    </html>

<script>
{
var data = window.prompt("digite a sua data de nascimento: ",);
data = data.split("/");
alert("dia: "+data[0]);
alert("mês: "+data[1]);
alert("ano: "+data[2]);

}



</script>


