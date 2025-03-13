
# Gestão de vagas - FrontEnd

Este projeto foi desenvolvido como parte da trilha de Java do programa Ignite, com foco na criação da interface gráfica do front-end. Ele utiliza o Thymeleaf, uma template engine integrada ao Spring, que facilita o desenvolvimento de interfaces dinâmicas e simplifica a integração com o back-end. O objetivo foi criar uma interface gráfica funcional e eficiente, mantendo a simplicidade e agilidade no desenvolvimento.

 ![Captura de tela 2025-03-13 132133](https://github.com/user-attachments/assets/6b9b1f7b-7d22-4cdc-94bd-ba994c8ef695)

 ![image](https://github.com/user-attachments/assets/04a35eb6-8341-44e2-a87c-83cd0872ae8c)

## Resetar o application.properties para o Ambiente Local

1 - Abra o arquivo src/main/resources/application.properties.

2 - Defina no seu application.properties em qual porta ele irá rodar e em seguida, você precisara definir qual a porta, o back-end está rodando: 
***
    server.port=8082
    host.api.gestao.vagas=http://localhost:8080 
***

3- Salve o arquivo.

## Executando a aplicação no Ambiente Local

1 - Instale as dependências do projeto:
***
    mvn clean install
***

2 - Inicie o projeto: 
***
    mvn spring-boot:run
***

A aplicação estará disponível em http://localhost:8082.
(Note que que, este 8082 deverá ser substituído pela porta que você configurou no seu application.properties.)


>Importante: Certifique-se de não enviar alterações para a branch main no GitHub, pois isso pode causar a interrupção do site hospedado no Render. Sempre trabalhe em uma branch separada e valide as mudanças antes de realizar qualquer merge.
