# Teste-Caixa-Branca

## Estrutura do Código
O código está organizado em uma classe Java chamada `User`. Esta classe tem os seguintes métodos e variáveis:

- `conectarBD()`: Este método estabelece uma conexão com o banco de dados MySQL e retorna a conexão.
- `verificarUsuario(String login, String senha)`: Este método verifica as credenciais do usuário no banco de dados e armazena o resultado em uma variável booleana `result` e o nome do usuário em `nome`.


## Avaliação - Aponte os erros que podem conter no código;

1- A ausência de documentação no código prejudica a compreensão do projeto.

2- Alguns identificadores de variáveis carecem de clareza, o que compromete a compreensão do propósito e conteúdo de cada variável. Utilizar nomes mais elucidativos e representativos tornaria o código mais legível e simplificaria a manutenção.

3- A falta de organização e espaços no código contribui para uma estrutura caótica, dificultando sua leitura. Um exemplo disso é a seção da consulta SQL, que, devido à carência de espaços, indentação e concatenação de strings, torna-se de difícil interpretação e suscetível a erros. Aprimorar a estrutura do código promoveria uma melhor legibilidade e minimizaria possíveis equívocos.

4- O código não aborda adequadamente exceções do tipo NullPointer. É crucial implementar tratamentos para esses casos, evitando possíveis falhas inesperadas.

5- A arquitetura do sistema carece de uma definição mais clara.

6- Não se observa o fechamento adequado de conexões no código. Essa omissão pode acarretar no esgotamento de recursos, prejudicando novas conexões e impactando o desempenho do aplicativo. Além disso, representa um risco de segurança, pois conexões não encerradas podem expor informações sensíveis

## Adicional

7. Os blocos "catch" vazios no código não tratam adequadamente os erros, tornando difícil identificar e resolver problemas, comprometendo a confiabilidade do programa. É importante adicionar tratamento de erros apropriado para lidar melhor com falhas.
