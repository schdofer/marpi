# Nome do Projeto

Descrever sucintamente em um parágrafo o projeto.

<!-- <style>
    .table-dev table { margin: 15px 0; }
    .table-dev table th { background-color: #2E8A4C; }
    .table-dev table tr td:first-child { background-color: #2E8A4C; }
    .table-hom table { margin: 15px 0; }
    .table-hom table th { background-color: #B4AC3C; }
    .table-hom table tr td:first-child { background-color: #B4AC3C; }
    .table-prod table { margin: 15px 0; }
    .table-prod table th { background-color: #993338; }
    .table-prod table tr td:first-child { background-color: #993338; }
</style> -->

<br />

| [ARQUITETURA](#1-arquitetura) | [AMBIENTE DE DESENVOLVIMENTO](#2-ambiente-de-desenvolvimento) | [TESTES](#3-testes) | [PUBLICAÇÃO](#4-publicação) | [VERSIONAMENTO](#5-versionamento) | [LICENÇA](#6-licença) | [CONTATOS](#7-contatos) |
| --------------------------- | ----------------------- | --------------------------------------------- | ------------------------- | ------------------------------- | ------------------- | --------------------- |


<br />

<br />

## **1. ARQUITETURA**

### **1.1. Tecnologias utilizadas**
- <img align="center" alt="Angular" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" /> Angular (Frontend)
- <img align="center" alt="Angular" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" />Google Charts (Frontend)
- <img align="center" alt="Angular" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" />Google Maps (Frontend)
- <img align="center" alt="Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" /> Java (Backend)
- <img align="center" alt="Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" /> Spring Boot (Backend)

<br />

### **1.2. Servidores e Links**

<div class="table-dev">

| Ambiente | Tipo | Servidor | Link (se existir) | Informaçõe adicionais |
| -------- | ---- | -------- | ----------------- | --------------------- |
| DEV | DATABASE SERVER | lpmpa-des3 | - | PostgreSQL 9 |
| DEV | APPLICATION SERVER | lpmpa-des3 | https://meulink.com | Docker com Nginx |
| DEV | WEB SERVER | lpmpa-des3 | https://meulink.com | Docker com Nginx |
| DEV | LOG SERVER | lpmpa-des3 | https://meulink.com | - |

</div>

<div class="table-hom">

<h5 align="center">HOMOLOGAÇÃO</h5>

<table align="center">
     <tr>
          <th>Tipo</th>
          <th>Servidor</th>
          <th>Link (se existir)</th>
          <th>Informaçõe adicionais</th>
     </tr>
     <tr>
          <td>DATABASE SERVER</td>
          <td>lpmpa-des3</td>
          <td> - </td>
          <td>PostgreSQL 9</td>
     </tr>
</table>

| Ambiente | Tipo | Servidor | Link (se existir) | Informaçõe adicionais |
| -------- | ---- | -------- | ----------------- | --------------------- |
| HOM | DATABASE SERVER | lpmpa-des3 | https://meulink.com | PostgreSQL 9 |
| HOM | APPLICATION SERVER | lpmpa-des3 | https://meulink.com |  Docker com Nginx |
| HOM | WEB SERVER | lpmpa-des3 | https://meulink.com |  Docker com Nginx |
| HOM | LOG SERVER | lpmpa-des3 | https://meulink.com | - |

</div>

<div class="table-prod">

| Ambiente | Tipo | Servidor | Link (se existir) | Informaçõe adicionais |
| -------- | ---- | -------- | ----------------- | --------------------- |
| PROD | DATABASE SERVER | lpmpa-des3 | https://meulink.com | PostgreSQL |
| PROD | APPLICATION SERVER | lpmpa-des3 | https://meulink.com | Docker com Nginx |
| PROD | WEB SERVER | lpmpa-des3 | https://meulink.com | Docker com Nginx |
| PROD | LOG SERVER | lpmpa-des3 | https://meulink.com | - |

</div>

<br />

### **1.3. Topologia**

![Texto alternativo](https://documentation.softexpert.com/pt-br/architecture/arquitetura_rede.png)

[Downlaod arquivo editável (Draw.io)](#)
<br />

<br />

## **2. AMBIENTE DE DESENVOLVIMENTO**

Instruções para que você consiga montar o ambiente de desenvolvimento e executar localmente.
<br />

### **2.1. Pré-requisitos**
Requisitos e ferramentas necessárias para executar o sistema.

Examplo:

- JDK 8
- Maven
- Eclipse IDE
- NPM
    - ```npm install npm@latest -g```
- Wildfly Versão 17
    - Modulo Keycloak instalado (veja mais em...link tutorial on github)
    - Modulo Postgres instalado (veja mais em...link tutorial on github)
<br />

### **2.2. Instalando**
Passo a passo com exemplos de como executar a aplicação.
1. Clone o repositório

    ```git clone git@github.com:schdofer/teste.git```

2. Instale as dependências (na pasta raíz do projeto)

     ```npm install```

3. Defina variáveis de ambiente

     ```ENV = local | dev | hom | prod```

4. Execute localmente

     ```ng serve```

<br />

<br />

## **3. TESTES**

Explica como executar os testes automatizados para este sistema.

1. Instale as dependências (na pasta raíz do projeto)

     ```npm install```

2. Execute os testes

     ```npm test```

<br />

<br />

## **4. PUBLICAÇÃO**

Informações adicionais sobre o deploy desta aplicação em desenvolvimento, homologação e produção.

<br />

<br />

## **5. VERSIONAMENTO**

Nós usamos [Semantic Versioning](http://semver.org/) para versionamento.

Para ver as versões disponíveis, veja as [tags neste repositorio](https://github.com/PurpleBooth/a-good-readme-template/tags).

<br />

<br />

## **6. LICENÇA**

Este projeto é liceciado com [CC0 1.0 Universal](LICENSE.md)

Creative Commons License - veja o arquivo [LICENSE.md](LICENSE.md) para maiores detalhes.

<br />

<br />

## **7. CONTATOS**

| Nome | E-mail | Telefone | Função | Órgão |
| ---- | ------ | -------- | ------ | ----- |
| Fernando Schneider da Cunha | fernando.cunha@procempa.com.br | (51) 3289-6357 | Desenvolvedor | PROCEMPA |
| Fernando Schneider da Cunha | fernando.cunha@procempa.com.br | (51) 3289-6357 | Desenvolvedor | PROCEMPA |
| Fernando Schneider da Cunha | fernando.cunha@procempa.com.br | (51) 3289-6357 | Desenvolvedor | PROCEMPA |
| Fernando Schneider da Cunha | fernando.cunha@procempa.com.br | (51) 3289-6357 | Desenvolvedor | PROCEMPA |