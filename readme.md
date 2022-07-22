### Sobre

Este projeto serve de base para levantar os containers contendo PHP8 + APACHE + MS-SQL, ele foi pensado primeiramente para utilização com Laravel mas pode ser util para qualquer aplicação em PHP.

clone os arquivos do repositorio.

crie um arquivo .env contendo as variaveis de ambiente necessárias para rodar seu projeto .

para subir os containers é necessário apontar a pasta que contem os arquivos de seu projeto , você pode fazer isso de duas formas :

 1 . alterando o docker-compose  passando sua pasta de forma fixa dentro do bloco de volumes.
 2 . passando sua pasta como parametro para inicialização da seguinte forma:

`PROJECT_PATH={pasta_raiz_do_projeto} docker compose up -d`

sua aplicação deve rodar em localhost na porta 3000 -  http://localhost:3000/