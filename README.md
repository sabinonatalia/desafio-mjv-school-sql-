# Atividade em grupo da semana MJV School Java

## Código Digital - Programação, Pesquisa, Educação

#### Autores
- [Gleyson Sampaio](https://github.com/glysns)

## Tabela Única SQL
O nosso desafio criar é uma jornada de instruções SQL contemplando comandos DDL + DML + DQL

#### Requisitos
1. Criação da tabela `tab_ficha_profissional` contendo os campos: Id (pk-auto increment), Nome, Email, Telefone, Endereco (Logradouro, Numero, Bairro, Cidade, Estado), Profissão, Salario Minimo Pretendido, Salario Maximo Pretendido, Estrangeiro ;
1. Descrever como o banco de dados escolhidos para tratar os tipos de dados em questão;
1. Apresenta todo o conteúdo em um arquivo .sql destacando as observações como comentário no script. (ver padrão de comentários no banco de dados selecionado).

#### Jornada

##### DDL

1. Criar a tabela citada acima contemplando os campos destacados, desconsiderando inicialmente o campo `profissão`;
1. Alterar a tabela para a inclusão do campo `profissão`;
1. Alterar a coluna `mail` para que ela possa chegar até 100 caracteres;

##### DML

1. Realizar um insert com 10 registros profissionais - SEM INFORMAR O VALOR DA COLUNA PROFISSÃO;
1. Definir como profissões por meio de `atualização inseridas, considerando a alteração` nos individualmente;
1. Excluir todos os registros que o campo `estrangeiro` for considerado verdadeiro;
1. O cadastro de Id=3 deve residir no endereço: Logradouro='PRACA DA SE', Numero = 'S/N', Bairro = 'CENTRO', Cidade = 'SAO PAULO', Estado = 'SP';

##### DQL

1. Retornar uma lista contendo os campos: Nome, Email, Profissão e Faixa Salarial ordenado por Profissão, Nome;
1. Retornar uma lista contendo os campos: Nome, Email, Profissão e Faixa Salarial ordenado por Profissão, Salario Máximo do maior para o menor;
1. Retornar uma lista com a seguinte informação concatenada e apelidada de nome_profissão: NOME + ' - ' + PROFISSAO;
1. Retornar uma lista contendo o nome da profissão e a quantidade de registros da profissão.
1. Retornar o registro com menor salário mínimo;
1. Retornar se existir o registro com a seguinte condição: Nome semelhante com 'MARCOS PAULO' e Salario Maximo `maior que` 1200 e Salario Maximo `menor ou igual que` 2000 e que o Estado é `entre` SP, RJ, SC .

##### Instruções

- Realizem todo o processo em uma base de dados, comentando cada etapa de evolução do projeto
- Para a apresentação do projeto, re-executem em uma nova base de dados o arquivo script.sql por etapas


######Referências

1. https://www.devmedia.com.br/sql-max-min-avg-sum-e-count/41218
1. https://docs.oracle.com/cloud/help/pt_BR/reportingcs_use/BILUG/GUID-4EE8C58D-391B-46A9-B0B3-9FA91B8159D1.htm#BILUG664
1. https://www.postgresqltutorial.com/postgresql-limit/
