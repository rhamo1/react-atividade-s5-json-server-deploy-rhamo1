# json-server-base

Essa API registra as notas dos alunos da escolinha do professor Jooj.

## Endpoints

POST /register - permite o registro de novos usuários, sendo que os campos obrigatórios são os de email e password;
POST /login - permite o login do usuário, desde que já tenha feito o registro;

GET /subjects - retorna todas as matérias da grade curricular (usuários autenticados ou não);
GET /grades - retorna \SOMENTE/ ao usuário autenticado as notas referentes às matérias.
