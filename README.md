## Full Stack Challenge - Pedro Fuques

Fala pessoal tudo bem? Segue algumas informações sobre o Projeto Desenvolvido para esse Desafio.

O Projeto foi divido em 2 solutions:

- frontend
- backend

## Projeto FrontEnd

O Projeto foi desenvolvido em ReactJS, portanto para rodar o projeto você deverá ter:

- NodeJs instalado na sua máquina, para isso digite no terminal “node -v”. 
Caso ainda não tenha instalado: https://nodejs.org/

- Para startar o Projeto:

Comando: 

### `yarn start`

Build do Projeto (Para realização de Deploy):

### `yarn build`


## Projeto BackEnd

O Projeto foi desenvolvido em Spring Boot.

- Para startar o Projeto:

Comando:

Acessar a pasta: backend\movie-list

### `mvnw spring-boot:run`

Obs: Para funcionar pela linha de comando, você precisará ter configurado o JAVA no seu Ambiente se for Windows por ex.
JAVA_HOME
Segue um link para ajuda: https://confluence.atlassian.com/confbr1/configurando-a-variavel-java_home-no-windows-933709538.html

Ou se preferir, poderá abrir o projeto BackEnd no VSCode, ir até a section: Spring Boot Dashboard, e clicar no Play.

Segue um link para ajuda, nas configurações do Spring Boot: https://dicasdejava.com.br/spring-boot-como-criar-a-estrutura-de-uma-aplicacao-web-do-zero-com-spring-initializr/

### Acesso as APIS:

- Para o desafio, foi utilizada a API: http://www.omdbapi.com/
- Foi necessário criar uma conta para receber uma chave de acesso válida.
- Segue a Chave que está sendo utilizada por tempo limitado: 4842a784

Ex: http://www.omdbapi.com/?t=lord&apikey=4842a784