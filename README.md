# Infnet-Arquitetura-Microsservicos

<br />
Infnet Arquitetura de Microsserviços Java [23E4_3]
<br />
<br />

## Projeto Final

Você deverá desenvolver 2 ou mais Microservices utilizando Spring Boot ou Quarkus ou ambos.

    Os MS precisam se comunicar entre si. Então, é obrigatório utilizar algum Client-side Load balancer e um Discovery Service.

    Também é obrigatório a utilização do Swagger para documentar os métodos.

Você deverá escolher pelo menos 2 dos temas abaixo e implementar na sua solução:

    Resiliência;
    Log Distribuído;
    Zipping;
    Spring Sleught (lembrando que no Quarkus a ferramenta de trace de log é outra);
    JWT - Keycloak (OPT);
    Monitoramento (pode utilizar a ferramenta que quiser).

Assim que terminar, salve o seu arquivo PDF e poste no Moodle. Utilize o seu nome para nomear o arquivo, identificando também a disciplina no seguinte formato: “nomedoaluno_nomedadisciplina_PD.PDF”.

## Entrega:

#### A sequência dos projetos é:

- Repositório com um projeto em Quarkus, com PanacheEntity, Swagger e Testes de Integração (API).

https://github.com/npmltech/About-Microservices-With-Quarkus

- Repositório com um projeto em Spring Boot para executar junto ao Service Discovery e o API Gateway.

https://github.com/npmltech/About-Microservices-Java

- Segundo projeto em Spring Boot para executar junto ao Service Discovery e o API Gateway.

https://github.com/npmltech/Mini-Projeto-Spring

- Repositório com o Eureka Service Discovery.

https://github.com/npmltech/Eureka-Service-Discovery

- Repositório com o API-Gateway do Spring Cloud e Zipkin como rastreamento de API.

https://github.com/npmltech/API-Gateway

## Execuções

**Todos os repositórios possuem os comandos para execução em seus respectivos README.md.**

**A sequência da execução para avaliar o API Gateway e os demais serviços é:**

1. Spring Eureka;
2. Os repositórios com os microsserviços em Spring Boot;
3. Executar a API-Gateway.

---
