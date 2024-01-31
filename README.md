# Lojinha
## Sistema fullstack de exemplo

## Tecnologias
- [NodeJS](https://nodejs.org/en/) - Ambiente de execução Javascript
- [VsCode](https://code.visualstudio.com/) - IDE
- [XAMPP](https://www.apachefriends.org/pt_br/index.html) - Mysql/MariaDB (XAMPP)
- Live Server - Extenção de servidor front-end VsCode para executar html

## Como testar
- 1 clone este repositório
- 2 Abra com VsCode
- 3 Abra o XAMPP e clique em Start no MySQL
- 4 Abra o banco de dados via shell ou phpMyadmin e rode o **script.sql** para criar e popular o banco de dados.
- 5 Abra o terminal (CMD ou BASH)
    - 5.1 Naveque até a pasta **./back** e instale as dependências
```bash
cd back
npm i
```
- 6 Inicie o Back-End
```bash
node server.js
ou
nodemon
ou
npx nodemon
```
7 - Acesse a pasta **front** e execute o index.html via Live Server.

# Prints das Telas
![Tela01](./prints/tela1.png)
![Tela01](./prints/tela2.png)
![Tela01](./prints/tela3.png)