# teste-fullstack-befective
[Back-End](#Back-End)
[Front-End](#Front-End)

## Back-End
Você deverá criar uma api, para um sistema de cadastro de clientes, tomando por base as seguintes regras:
1- Deverá ser usado o framework express;
2- A api deverá executar um CRUD em um banco de dados
3- A api deverá ter endpoints públicos e privados. Os privados devem ser autenticados utilizando JWT.
4- Usuário deverá ser capaz de se autenticar, através de email e senha, para realizar as ações de CRUD.

** serão considerados diferenciais: 
1- O Uso de um ORM para a comunicação e transação com o Banco de Dados
2- Realizar a persistência utilizando um banco de dados Postgres
3- Uso de migrations 
4- Uso de typeScript
5- Design Paterns
6- Código limpo e de fácil entendimento.


### Model de Users
id - autoincrement e primary key<br/>
username - varchar<br/>
email - varchar<br/>
password - deve ser encriptado utilizando o bcryptjs <br/>

### Model de Contacts
id - autoincrement e primary key<br/>
name - varchar<br/>
email - varchar<br/>
mobile - varchar<br/>



## Front-End
Usando a API que você criou, crie agora o front da aplicação.
Esse front-end deverá consumir as apis criadas, permitindo ao usuário fazer o login e, após logado, cadastrar clientes, listar, alterar, excluir;

1- A aplicação deverá ser construída utilizando React.JS 
2- Poderá ser usado Bootstrap 

** serão considerados diferencias:
1- Uso de boas práticas,
2- código limpo e de fácil entendimento,
3- uso de CSS customizado ao invés de frameworks.



## Após a conclusão
Quando finalizar o teste, tando de front quanto de backend, deverá criar um repositório público para cada uma das aplicações (front / Back) e enviar o link para os emails: paulo.tozzi@befective.com e marciano.verdi@befective.com

Deverá ser feito o deploy do backend em alguma plataforma (ex. Heroku) e, no READ.ME do repo deverá existir uma documentação de como testá-la.

O Front-end deverá também ter seu deploy em alguma plataforma (ex.neflify) e deve conter no READ.ME do repo o usuário/senha para login.

