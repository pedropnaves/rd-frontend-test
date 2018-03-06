# \<DesafioFrontend />

**Objetivo:**
Implementar uma aplicação para gerenciar os candidatos que estão em processo seletivo na empresa XYZ. Esta aplicação necessita ser executada nos navegadores mais recentes do mercado.

**API:** [https://randomuser.me/](https://randomuser.me/)

**Layout (Marvel):** [https://marvelapp.com/39776de](https://marvelapp.com/39776de)

**Estimativa:**
Dependendo da sua experiência e/ou das ferramentas escolhidas, você pode precisar de mais ou menos tempo para realizar o desafio.
Lembre-se que vamos avaliar a sua capacidade de estimativa e também a sua capacidade em executar o projeto no tempo planejado.

Ao efetuar a estimativa para realização, por favor avise o RH.


### **Requisitos** ###
* Eu como usuário, desejo visualizar a listagem de candidatos;
* Eu como usuário, desejo pesquisar um determinado usuário conforme seu nome ou email;
* Eu como usuário, desejo que seja apresentado a foto de 1 usuário qualquer no menu da Minha Conta (Buscar da API);
* Eu como usuário, desejo visualizar as informação de cada candidato (Nome, email, telefone, cidade e estado);
* Eu como usuário, desejo enviar para a "LIXEIRA" 1 usuário da listagem geral;
* Eu como usuário, desejo marcar como "ATENDIDO" 1 usuário da listagem geral;
* Eu como usuário, desejo navegar nos filtros laterais conforme a interação executada;
* Eu como usuário, desejo que ao clicar em um item da listagem seja apresentado as informações do usuário em uma nova tela;
* Eu como usuário, desejo que ao visualizar a informação de 1 usuário seja possível voltar a tela anterior;


### **Especificações Técnicas** ###
O sistema deve seguir o layout do Marvel, com isso as funcionalidades a serem desenvolvidas serão avaliadas de acordo com o seu nível.

**Nível Junior**
* Layout conforme o Marvel (Dê o seu máximo);
* A aplicação deve se comportar como uma Single Page Application;
* Utilização de Rotas para navegação;
* Ao navegar entre as rotas, as informaões devem ser mantidas e não pode ter refresh da listagem;
* A busca deverá ser executado na listagem atual;
* (Desejável/Bônus) Gerenciamento de estado;
* (Desejável/Bônus) Paginação;


**Nível Pleno**
* Todos os requisitos do nível anterior;
* Paginação númerada;
* Armazenar todas as informações no estado utilizando a arquitetura Flux (Redux, Vuex e etc);
* Ao navegar nos filtros laterais, todas as informações devem já estar no estado;
* Ao pesquisar, deverá ser armazenado no estado todas as pesquisas realizadas na sessão atual;
* Configurar eslint;
* (Desejável/Bônus) Microinteração da interface;
* (Desejável/Bônus) Testes unitários;
* (Desejável/Bônus) Utilizar algum bundle size (Webpack, Rollup ou Parcel);

**Nível Senior**
* Todos os requisitos dos níveis anterior;
* Paginação infinita ao invés da númerada;
* Microinteração da interface;
* Testes unitários (mínimo de 70% de coverage);
* Execução dos testes unitários no build do projeto;
* Utilizar ferramenta para internacionalização (criar bundle de linguagem i18n);
* Utilizar algum bundle size (Webpack, Rollup ou Parcel);
* Utilizar alguma metodologia para CSS (BEM, SMACSS, OOCSS, ATOMIC CSS, DRY CSS);
* (Desejável/Bônus) Realizar testes de snapshot;
* (Desejável/Bônus) Apresentação do coverage dos testes unitários;
* (Desejável/Bônus) Criar o Story Book dos Components;
* (Desejável/Bônus) Separar Dumb Components e publicá-los no NPM;
* (Desejável/Bônus) CSS in JS

### ** Desejável *** ###
* A aplicação deve ser responsiva (mobile, tablet, desktop);

### **Especificações Gerais** ###
* Utilizar React, Vue ou Angular;
* Utilizar pré-processador de CSS (Fique a vontade para usar alguma lib/framework css);
* ECMAScript 6;
* Flexbox;
* Documentar no mínimo, o como executar o projeto;
* Armazenar o código fonte no Github;
