# API_PYTHON
WORKING ON PYTHON APP API`S

# Understanding APIs and Web API Types (Compreendendo APIs e Tipos de Web APIs)

This document provides a comprehensive overview of Application Programming Interfaces (APIs), explaining what they are, how Web APIs facilitate communication between clients and servers over the internet, and the characteristics of various popular Web API architectural styles.

---

## English Version

### 1. What is an API?

An **Application Programming Interface (API)** is a fundamental concept in software development.
* **Application Programming Interface.**
    * **Explanation:** It serves as a crucial intermediary that allows different software components or applications to communicate with each other. It's not the software itself, but a set of rules and definitions that dictate how software should interact.
* **Set of communication rules and abilities.**
    * **Explanation:** An API specifies the methods, data formats, and protocols that software components must follow to send requests and receive responses, enabling seamless interaction.
* **Enables interactions between software applications.**
    * **Explanation:** APIs abstract away the complexities of underlying systems, allowing developers to integrate functionalities from other software without needing to understand their internal workings. For example, an email client uses an API to send emails via an email server.

### 2. Web APIs, Clients, and Servers

Web APIs are a specific type of API designed to communicate over the internet, typically following a client-server model.

* **Web APIs communicate over the internet using HTTP.**
    * **Explanation:** The Hypertext Transfer Protocol (HTTP) is the foundation of data communication for the World Wide Web. Web APIs leverage HTTP methods (like GET, POST, PUT, DELETE) to facilitate requests and responses between different systems.
* **Client sends a request message to a Server.**
    * **Explanation:** In this model, a "client" (e.g., a web browser, mobile app, or another server) initiates communication by sending a request for data or to perform an action to a "server."
* **Server returns a response message to the Client.**
    * **Explanation:** The "server," which hosts the API, processes the client's request and sends back a response containing the requested data or confirmation of the action performed.
* **Request/Response cycle.**
    * **Explanation:** This describes the fundamental interaction pattern where a client makes a request and waits for a server to send back a response, forming a complete communication loop over the internet.

### 3. Types of Web APIs

Different architectural styles exist for designing Web APIs, each with its own philosophy and strengths.

* **SOAP** (Simple Object Access Protocol)
    * **Focus on strict and formal API design.**
        * **Explanation:** SOAP APIs are characterized by their strong typing, reliance on XML for message formatting, and strict contracts defined by WSDL (Web Services Description Language). This formality ensures high interoperability and discoverability.
    * **Enterprise applications.**
        * **Explanation:** Due to their robustness, security features (like WS-Security), and built-in error handling, SOAP APIs have historically been favored for complex enterprise-level applications, particularly in highly regulated industries.

* **REST** (Representational State Transfer)
    * **Focus on simplicity & scalability.**
        * **Explanation:** REST APIs leverage standard HTTP methods and are designed to be stateless, promoting simplicity in their implementation and making them highly scalable. They often use JSON or XML for data exchange.
    * **Most common API architecture.**
        * **Explanation:** REST has become the dominant architectural style for web services due to its ease of use, flexibility, and widespread adoption by web browsers and mobile applications.

* **GraphQL**
    * **Focus on flexibility.**
        * **Explanation:** GraphQL is a query language for APIs that allows clients to request exactly the data they need and nothing more, even from complex nested structures. This contrasts with REST, where clients often receive fixed data structures.
    * **Optimized for performance.**
        * **Explanation:** By allowing clients to fetch multiple resources in a single request and avoid over-fetching or under-fetching data, GraphQL can significantly reduce network calls and data transfer, leading to improved performance, especially for mobile applications or clients with varying data needs.

---

## Versão em Português

# Compreendendo APIs e Tipos de Web APIs

Este documento fornece uma visão geral abrangente das Interfaces de Programação de Aplicações (APIs), explicando o que são, como as Web APIs facilitam a comunicação entre clientes e servidores pela internet, e as características de vários estilos arquiteturais populares de Web APIs.

---

## Versão em Português

### 1. O que é uma API?

Uma **Interface de Programação de Aplicações (API)** é um conceito fundamental no desenvolvimento de software.
* **Interface de Programação de Aplicações.**
    * **Explicação:** Ela serve como um intermediário crucial que permite que diferentes componentes ou aplicações de software se comuniquem entre si. Não é o software em si, mas um conjunto de regras e definições que ditam como o software deve interagir.
* **Conjunto de regras e habilidades de comunicação.**
    * **Explicação:** Uma API especifica os métodos, formatos de dados e protocolos que os componentes de software devem seguir para enviar solicitações e receber respostas, permitindo uma interação perfeita.
* **Permite interações entre aplicações de software.**
    * **Explicação:** APIs abstraem as complexidades dos sistemas subjacentes, permitindo que os desenvolvedores integrem funcionalidades de outros softwares sem precisar entender seus funcionamentos internos. Por exemplo, um cliente de e-mail usa uma API para enviar e-mails através de um servidor de e-mail.

### 2. Web APIs, Clientes e Servidores

Web APIs são um tipo específico de API projetada para se comunicar pela internet, tipicamente seguindo um modelo cliente-servidor.

* **Web APIs se comunicam pela internet usando HTTP.**
    * **Explicação:** O Protocolo de Transferência de Hipertexto (HTTP) é a base da comunicação de dados para a World Wide Web. Web APIs utilizam métodos HTTP (como GET, POST, PUT, DELETE) para facilitar solicitações e respostas entre diferentes sistemas.
* **Cliente envia uma mensagem de solicitação para um Servidor.**
    * **Explicação:** Neste modelo, um "cliente" (ex: um navegador web, aplicativo móvel ou outro servidor) inicia a comunicação enviando uma solicitação de dados ou para realizar uma ação a um "servidor".
* **Servidor retorna uma mensagem de resposta para o Cliente.**
    * **Explicação:** O "servidor", que hospeda a API, processa a solicitação do cliente e envia de volta uma resposta contendo os dados solicitados ou a confirmação da ação realizada.
* **Ciclo de Requisição/Resposta.**
    * **Explicação:** Isso descreve o padrão de interação fundamental onde um cliente faz uma solicitação e espera que um servidor envie uma resposta, formando um loop de comunicação completo pela internet.

### 3. Tipos de Web APIs

Diferentes estilos arquiteturais existem para projetar Web APIs, cada um com sua própria filosofia e pontos fortes.

* **SOAP** (Simple Object Access Protocol)
    * **Foco em design de API estrito e formal.**
        * **Explicação:** APIs SOAP são caracterizadas por sua tipagem forte, dependência de XML para formatação de mensagens e contratos estritos definidos por WSDL (Web Services Description Language). Essa formalidade garante alta interoperabilidade e detectabilidade.
    * **Aplicações empresariais.**
        * **Explicação:** Devido à sua robustez, recursos de segurança (como WS-Security) e tratamento de erros integrado, as APIs SOAP foram historicamente favorecidas para aplicações de nível empresarial complexas, particularmente em indústrias altamente regulamentadas.

* **REST** (Representational State Transfer)
    * **Foco em simplicidade e escalabilidade.**
        * **Explicação:** APIs REST utilizam métodos HTTP padrão e são projetadas para serem stateless (sem estado), promovendo a simplicidade em sua implementação e tornando-as altamente escaláveis. Elas frequentemente usam JSON ou XML para troca de dados.
    * **Arquitetura de API mais comum.**
        * **Explicação:** REST tornou-se o estilo arquitetural dominante para serviços web devido à sua facilidade de uso, flexibilidade e ampla adoção por navegadores web e aplicações móveis.

* **GraphQL**
    * **Foco em flexibilidade.**
        * **Explicação:** GraphQL é uma linguagem de consulta para APIs que permite aos clientes solicitar exatamente os dados de que precisam e nada mais, mesmo de estruturas aninhadas complexas. Isso contrasta com o REST, onde os clientes frequentemente recebem estruturas de dados fixas.
    * **Otimizado para desempenho.**
        * **Explicação:** Ao permitir que os clientes busquem múltiplos recursos em uma única solicitação e evitem o over-fetching (buscar dados em excesso) ou under-fetching (buscar dados insuficientes), o GraphQL pode reduzir significativamente as chamadas de rede e a transferência de dados, levando a um desempenho aprimorado, especialmente para aplicações móveis ou clientes com necessidades de dados variadas.
     

# API Requests with urllib (Solicitações de API com urllib)

This document explains how to make a basic API request in Python using the built-in `urllib.request` module. We will demonstrate how to fetch data from a local API endpoint and handle the response.

---

## English Version

### Understanding the API Request

In this context, we are interacting with a Music Catalog API, specifically its `Lyrics API` endpoint, which retrieves a "lyric of the day." The Uniform Resource Locator (URL) `http://localhost:3000/lyrics/` specifies where this API can be accessed.

The Python code provided demonstrates a basic way to perform this API request using `urllib.request`:


```python
from urllib.request import urlopen

with urlopen('http://localhost:3000/lyrics/') as response:
  
  # Use the correct function to read the response data from the response object
  data = response.read()
  encoding = response.headers.get_content_charset()

  # Decode the response data so you can print it as a string later
  string = data.decode(encoding)
  
  print(string)
```

### Code Explanation:
1.from urllib.request import urlopen:

 * **This line imports the urlopen function from Python's urllib.request module. The urlopen function is used to open a URL, returning a file-like object that can be read from.

2. with urlopen('http://localhost:3000/lyrics/') as response::

* **This initiates the API request. urlopen() connects to the specified URL (http://localhost:3000/lyrics/).
* **The with statement ensures that the connection (the response object) is properly closed after its block of code is executed, even if errors occur.
* **The result of urlopen() is assigned to the response variable, which is a HTTPResponse object.

3. data = response.read():

 * **The read() method of the response object is called. This function reads the entire content of the API's response. The data is received as a sequence of bytes.

4. encoding = response.headers.get_content_charset():

 * **APIs often specify the character encoding of their response in the HTTP headers (e.g., 'utf-8'). This line retrieves that encoding from the response.headers. Knowing the correct encoding is vital for correctly converting bytes to a readable string.

5. string = data.decode(encoding):

 * **Since data is in bytes, it needs to be decode()d into a string so it can be easily read and processed by Python. The encoding obtained in the previous step is used for this conversion. This turns the raw byte data into a human-readable text.

6.print(string):

 * **Finally, the decoded string (which contains the "lyric of the day" quote) is printed to the console.

This simple example demonstrates the fundamental steps of making an HTTP GET request, reading the response, and decoding it into a usable string format using Python's standard library.


## Versão em Português

### Solicitações de API com urllib

Este documento explica como fazer uma solicitação de API básica em Python usando o módulo *urllib.request* integrado. Demonstraremos como buscar dados de um endpoint de API local e lidar com a resposta.


## Versão em Português

### Compreendendo a Solicitação de API
Neste contexto, estamos interagindo com uma API de Catálogo de Músicas, especificamente seu endpoint da API Lyrics, que recupera uma "citação da letra do dia". O Uniform Resource Locator (URL) http://localhost:3000/lyrics/ especifica onde esta API pode ser acessada.

O código Python fornecido demonstra uma maneira básica de realizar esta solicitação de API usando *urllib.request*:

```python
from urllib.request import urlopen

with urlopen('http://localhost:3000/lyrics/') as response:
  
  # Use a função correta para ler os dados da resposta do objeto response
  data = response.read()
  encoding = response.headers.get_content_charset()

  # Decodifique os dados da resposta para que você possa imprimi-los como uma string mais tarde
  string = data.decode(encoding)
  
  print(string)
```

## Explicação do Código:

1. from urllib.request import urlopen:

* **Esta linha importa a função urlopen do módulo urllib.request do Python. A função urlopen é usada para abrir uma URL, retornando um objeto semelhante a um arquivo que pode ser lido.


2. with urlopen('http://localhost:3000/lyrics/') as response::

* **Isso inicia a solicitação de API. urlopen() conecta-se à URL especificada (http://localhost:3000/lyrics/).
* **A instrução with garante que a conexão (o objeto response) seja fechada corretamente após a execução de seu bloco de código, mesmo que ocorram erros.
* **O resultado de urlopen() é atribuído à variável response, que é um objeto HTTPResponse.

3. data = response.read():

 *O método read() do objeto response é chamado. Esta função lê todo o conteúdo da resposta da API. Os dados são recebidos como uma sequência de bytes.

4. encoding = response.headers.get_content_charset():

*APIs frequentemente especificam a codificação de caracteres de sua resposta nos cabeçalhos HTTP (ex: 'utf-8'). Esta linha recupera essa codificação de response.headers. Conhecer a codificação correta é vital para converter corretamente bytes em uma string legível.

5. string = data.decode(encoding):

*Como data está em bytes, ela precisa ser decode()ficada em uma string para que possa ser facilmente lida e processada pelo Python. A encoding obtida na etapa anterior é usada para esta conversão. Isso transforma os dados brutos em bytes em um texto legível por humanos.

6. print(string):

*Finalmente, a string decodificada (que contém a citação da "letra do dia") é impressa no console.

Este exemplo simples demonstra os passos fundamentais para fazer uma solicitação HTTP GET, ler a resposta e decodificá-la para um formato de string utilizável usando a biblioteca padrão do Python.

### Requests 
```python
# Import the requests package
import requests

# Pass the API URL to the get function
response = requests.get('http://localhost:3000/lyrics')

# Print out the text attribute of the response object
print(response.text)
```

# HTTP Verbs and Their Actions in API Interactions (Verbos HTTP e Suas Ações em Interações de API)

This document outlines the fundamental HTTP verbs commonly used in API design, detailing the actions they represent and their typical use cases in managing resources. These verbs are crucial for defining how clients interact with web servers to perform operations on data.

---

## English Version

### Understanding HTTP Actions (Verbs)

HTTP verbs (also known as methods) define the type of action a client wants to perform on a resource identified by a URL. They are a core part of RESTful API design.

| Verb   | Action  | Description                                |
| :----- | :------ | :----------------------------------------- |
| **GET** | Read    | Check the mailbox contents                 |
| **POST** | Create  | Drop a new package in the mailbox          |
| **PUT** | Update  | Replace all packages with a new one        |
| **DELETE** | Delete  | Remove all packages from the mailbox       |

* **GET (Read):**
    * **Description:** This verb is used to retrieve data from a specified resource. It should only fetch data and have no other effect on the server's data.
    * **Analogy:** Checking the mailbox contents means you are looking inside to see what is there, without changing anything.

* **POST (Create):**
    * **Description:** This verb is used to submit data to a specified resource, often causing a change in state or the creation of a new resource on the server.
    * **Analogy:** Dropping a new package in the mailbox implies you are adding a new item, creating a new entry in the mailbox's contents.

* **PUT (Update):**
    * **Description:** This verb is used to update an existing resource or create a resource if it does not exist. It typically replaces the entire resource with the payload sent.
    * **Analogy:** Replacing all packages with a new one signifies that the entire content of the mailbox is being overwritten or substituted with a new set of packages.

* **DELETE (Delete):**
    * **Description:** This verb is used to remove a specified resource from the server.
    * **Analogy:** Removing all packages from the mailbox means you are emptying it, deleting its entire contents.

These verbs provide a clear and standardized way for clients and servers to communicate intentions, making APIs predictable and easier to use.

---

## Versão em Português

# Verbos HTTP e Suas Ações em Interações de API

Este documento descreve os verbos HTTP fundamentais comumente usados no design de APIs, detalhando as ações que eles representam e seus casos de uso típicos no gerenciamento de recursos. Esses verbos são cruciais para definir como os clientes interagem com os servidores web para realizar operações em dados.

---

## Versão em Português

### Compreendendo as Ações HTTP (Verbos)

Verbos HTTP (também conhecidos como métodos) definem o tipo de ação que um cliente deseja realizar em um recurso identificado por uma URL. Eles são uma parte central do design de APIs RESTful.

| Verbo    | Ação     | Descrição                                 |
| :------- | :------- | :---------------------------------------- |
| **GET** | Ler      | Verificar o conteúdo da caixa de correio  |
| **POST** | Criar    | Colocar um novo pacote na caixa de correio |
| **PUT** | Atualizar | Substituir todos os pacotes por um novo    |
| **DELETE** | Excluir  | Remover todos os pacotes da caixa de correio |

* **GET (Ler):**
    * **Descrição:** Este verbo é usado para recuperar dados de um recurso especificado. Ele deve apenas buscar dados e não ter nenhum outro efeito nos dados do servidor.
    * **Analogia:** Verificar o conteúdo da caixa de correio significa que você está olhando para ver o que há dentro, sem alterar nada.

* **POST (Criar):**
    * **Descrição:** Este verbo é usado para submeter dados a um recurso especificado, frequentemente causando uma mudança de estado ou a criação de um novo recurso no servidor.
    * **Analogia:** Colocar um novo pacote na caixa de correio implica que você está adicionando um novo item, criando uma nova entrada no conteúdo da caixa de correio.

* **PUT (Atualizar):**
    * **Descrição:** Este verbo é usado para atualizar um recurso existente ou criar um recurso se ele não existir. Ele tipicamente substitui todo o recurso pelo payload enviado.
    * **Analogia:** Substituir todos os pacotes por um novo significa que todo o conteúdo da caixa de correio está sendo sobrescrito ou substituído por um novo conjunto de pacotes.

* **DELETE (Excluir):**
    * **Descrição:** Este verbo é usado para remover um recurso especificado do servidor.
    * **Analogia:** Remover todos os pacotes da caixa de correio significa que você está esvaziando-a, excluindo todo o seu conteúdo.

Esses verbos fornecem uma maneira clara e padronizada para clientes e servidores comunicarem intenções, tornando as APIs previsíveis e mais fáceis de usar.


# Request and Response Message Anatomy in HTTP (Anatomia da Mensagem de Requisição e Resposta em HTTP)

When interacting with web services, communication primarily occurs through HTTP request and response messages. Each message follows a standard structure, divided into a starting line, headers, and an optional body. Understanding this anatomy is fundamental for working with web APIs.

---

## English Version

### 1. Request Message

A client sends a request message to a server to ask for a resource or to submit data.

* **Request Line:** This is the first line of the request message.
    * **Example:** `GET /users/42 HTTP/1.1`
    * **Components:**
        * **Method (GET):** The HTTP verb indicating the action the client wants to perform (e.g., GET to retrieve, POST to create, PUT to update, DELETE to remove).
        * **Path (/users/42):** The specific resource the client is requesting or interacting with on the server.
        * **HTTP Version (HTTP/1.1):** The version of the HTTP protocol being used.

* **Headers:** These lines follow the request line and provide additional information about the request or the client.
    * **Example:**
        * `Host: datacamp.com`: Specifies the domain name of the server the request is being sent to.
        * `Accept: application/json`: Informs the server about the media types the client expects to receive in the response (e.g., JSON format).

* **Body:** This is an optional part of the request message, used primarily with methods like POST or PUT to send data to the server (e.g., form data, JSON payload for creating a new resource). For a GET request, the body is typically empty.

### 2. Response Message

A server sends a response message back to the client after receiving and processing a request.

* **Response Line:** This is the first line of the response message.
    * **Example:** `HTTP/1.1 200 OK`
    * **Components:**
        * **HTTP Version (HTTP/1.1):** The version of the HTTP protocol used by the server.
        * **Status Code (200):** A three-digit number indicating the status of the request (e.g., 200 OK means success, 404 Not Found means the resource was not found, 500 Internal Server Error means a server-side error).
        * **Status Text (OK):** A short, human-readable text corresponding to the status code.

* **Headers:** These lines follow the response line and provide metadata about the response or the server.
    * **Example:**
        * `Content-Type: application/json`: Specifies the media type of the data contained in the response body.
        * `Content-Language: en-US`: Indicates the natural language of the intended audience for the response.
        * `Last-Modified: Wed, 21 Oct 2023 07:28:00 GMT`: Provides the date and time the resource was last modified.

* **Body:** This is the main part of the response message, containing the actual data requested by the client or other relevant information.
    * **Example (JSON Body):**
        ```json
        {
            "id": 42,
            "name": "John Doe",
            "age": 30,
            "email": "john@datacamp.com"
        }
        ```
        * **Explanation:** This example shows a JSON object, a common format for API responses, containing details about a user with ID 42.

This structured communication allows clients and servers to interact efficiently and predictably over the web.

---

## Versão em Português

# Anatomia da Mensagem de Requisição e Resposta em HTTP

Ao interagir com serviços web, a comunicação ocorre principalmente através de mensagens de requisição e resposta HTTP. Cada mensagem segue uma estrutura padrão, dividida em uma linha inicial, cabeçalhos e um corpo opcional. Compreender essa anatomia é fundamental para trabalhar com APIs web.

---

## Versão em Português

### 1. Mensagem de Requisição

Um cliente envia uma mensagem de requisição para um servidor para pedir um recurso ou para enviar dados.

* **Linha de Requisição:** Esta é a primeira linha da mensagem de requisição.
    * **Exemplo:** `GET /users/42 HTTP/1.1`
    * **Componentes:**
        * **Método (GET):** O verbo HTTP indicando a ação que o cliente deseja realizar (ex: GET para recuperar, POST para criar, PUT para atualizar, DELETE para remover).
        * **Caminho (/users/42):** O recurso específico que o cliente está solicitando ou interagindo no servidor.
        * **Versão HTTP (HTTP/1.1):** A versão do protocolo HTTP que está sendo utilizada.

* **Cabeçalhos (Headers):** Essas linhas seguem a linha de requisição e fornecem informações adicionais sobre a requisição ou o cliente.
    * **Exemplo:**
        * `Host: datacamp.com`: Especifica o nome de domínio do servidor para o qual a requisição está sendo enviada.
        * `Accept: application/json`: Informa ao servidor sobre os tipos de mídia que o cliente espera receber na resposta (ex: formato JSON).

* **Corpo (Body):** Esta é uma parte opcional da mensagem de requisição, utilizada principalmente com métodos como POST ou PUT para enviar dados ao servidor (ex: dados de formulário, payload JSON para criar um novo recurso). Para uma requisição GET, o corpo tipicamente está vazio.

### 2. Mensagem de Resposta

Um servidor envia uma mensagem de resposta de volta ao cliente após receber e processar uma requisição.

* **Linha de Resposta:** Esta é a primeira linha da mensagem de resposta.
    * **Exemplo:** `HTTP/1.1 200 OK`
    * **Componentes:**
        * **Versão HTTP (HTTP/1.1):** A versão do protocolo HTTP utilizada pelo servidor.
        * **Código de Status (200):** Um número de três dígitos indicando o status da requisição (ex: 200 OK significa sucesso, 404 Not Found significa que o recurso não foi encontrado, 500 Internal Server Error significa um erro no lado do servidor).
        * **Texto de Status (OK):** Um texto curto e legível correspondente ao código de status.

* **Cabeçalhos (Headers):** Essas linhas seguem a linha de resposta e fornecem metadados sobre a resposta ou o servidor.
    * **Exemplo:**
        * `Content-Type: application/json`: Especifica o tipo de mídia dos dados contidos no corpo da resposta.
        * `Content-Language: en-US`: Indica a linguagem natural do público-alvo para a resposta.
        * `Last-Modified: Wed, 21 Oct 2023 07:28:00 GMT`: Fornece a data e hora em que o recurso foi modificado pela última vez.

* **Corpo (Body):** Esta é a parte principal da mensagem de resposta, contendo os dados reais solicitados pelo cliente ou outras informações relevantes.
    * **Exemplo (Corpo JSON):**
        ```json
        {
            "id": 42,
            "name": "John Doe",
            "age": 30,
            "email": "john@datacamp.com"
        }
        ```
        * **Explicação:** Este exemplo mostra um objeto JSON, um formato comum para respostas de API, contendo detalhes sobre um usuário com ID 42.

Essa comunicação estruturada permite que clientes e servidores interajam de forma eficiente e previsível pela web.


# HTTP Status Codes: Categories and Common Examples (Códigos de Status HTTP: Categorias e Exemplos Comuns)

HTTP status codes are three-digit numbers returned by a server in response to a client's HTTP request. They indicate whether a specific HTTP request has been successfully completed. These codes are categorized into five classes, providing a standardized way to communicate the outcome of an interaction.

---

## English Version

### Status Code Categories

HTTP status codes are grouped into five main categories, each representing a general class of response:

* **1XX : Informational responses**
    * **Explanation:** These codes indicate that the request has been received and understood. They are provisional responses, consisting only of the status line and optional headers, and are terminated by an empty line. They serve to inform the client that the request is still being processed.

* **2XX : Successful responses**
    * **Explanation:** These codes signify that the client's request was successfully received, understood, and accepted. They indicate that the action requested by the client was completed.

* **3XX : Redirection messages**
    * **Explanation:** These codes inform the client that further action needs to be taken to complete the request. This often means the resource has moved, and the client should make a new request to a different URL.

* **4XX : Client error responses**
    * **Explanation:** These codes indicate that there was an error with the client's request. The server perceives that the client has made a mistake (e.g., incorrect syntax, invalid credentials, or requesting a non-existent resource).

* **5XX : Server error responses**
    * **Explanation:** These codes indicate that the server encountered an error while attempting to fulfill a seemingly valid request from the client. This means the problem lies with the server, not the client's request.

### Frequently Used Status Codes

While there are many HTTP status codes, some are encountered far more frequently in web development and API interactions:

* **200 : OK**
    * **Explanation:** The most common successful response code. It indicates that the request has succeeded. The meaning of a success depends on the HTTP method (e.g., for GET, the resource has been fetched and transmitted; for POST, the resource describing the result of the action is transmitted).

* **404 : Not Found**
    * **Explanation:** This client error status code indicates that the server cannot find the requested resource. It is one of the most well-known error messages, signifying that the URL does not correspond to any available resource on the server.

* **500 : Internal Server Error**
    * **Explanation:** This generic server error message indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. It's a catch-all error for server-side issues when no more specific error code is appropriate.

---

## Versão em Português

# Códigos de Status HTTP: Categorias e Exemplos Comuns

Códigos de status HTTP são números de três dígitos retornados por um servidor em resposta a uma requisição HTTP de um cliente. Eles indicam se uma requisição HTTP específica foi concluída com sucesso. Esses códigos são categorizados em cinco classes, fornecendo uma maneira padronizada de comunicar o resultado de uma interação.

---

## Versão em Português

### Categorias de Códigos de Status

Os códigos de status HTTP são agrupados em cinco categorias principais, cada uma representando uma classe geral de resposta:

* **1XX : Respostas informativas**
    * **Explicação:** Esses códigos indicam que a requisição foi recebida e compreendida. São respostas provisórias, consistindo apenas da linha de status e cabeçalhos opcionais, e são terminadas por uma linha vazia. Servem para informar ao cliente que a requisição ainda está sendo processada.

* **2XX : Respostas de sucesso**
    * **Explicação:** Esses códigos significam que a requisição do cliente foi recebida, compreendida e aceita com sucesso. Eles indicam que a ação solicitada pelo cliente foi concluída.

* **3XX : Mensagens de redirecionamento**
    * **Explicação:** Esses códigos informam ao cliente que ações adicionais precisam ser tomadas para completar a requisição. Isso frequentemente significa que o recurso se moveu, e o cliente deve fazer uma nova requisição para uma URL diferente.

* **4XX : Respostas de erro do cliente**
    * **Explicação:** Esses códigos indicam que houve um erro com a requisição do cliente. O servidor percebe que o cliente cometeu um erro (ex: sintaxe incorreta, credenciais inválidas ou requisição de um recurso não existente).

* **5XX : Respostas de erro do servidor**
    * **Explicação:** Esses códigos indicam que o servidor encontrou um erro ao tentar atender a uma requisição aparentemente válida do cliente. Isso significa que o problema está no servidor, não na requisição do cliente.

### Códigos de Status Frequentemente Usados

Embora existam muitos códigos de status HTTP, alguns são encontrados com muito mais frequência no desenvolvimento web e em interações de API:

* **200 : OK**
    * **Explicação:** O código de resposta de sucesso mais comum. Indica que a requisição foi bem-sucedida. O significado de um sucesso depende do método HTTP (ex: para GET, o recurso foi buscado e transmitido; para POST, o recurso que descreve o resultado da ação é transmitido).

* **404 : Not Found (Não Encontrado)**
    * **Explicação:** Este código de status de erro do cliente indica que o servidor não consegue encontrar o recurso solicitado. É uma das mensagens de erro mais conhecidas, significando que a URL não corresponde a nenhum recurso disponível no servidor.

* **500 : Internal Server Error (Erro Interno do Servidor)**
    * **Explicação:** Esta mensagem genérica de erro do servidor indica que o servidor encontrou uma condição inesperada que o impediu de atender à requisição. É um erro "catch-all" para problemas do lado do servidor quando nenhum código de erro mais específico é apropriado.

# HTTP Methods in API Requests: Examples (Métodos HTTP em Requisições de API: Exemplos)

HTTP methods (or verbs) define the type of action a client intends to perform on a resource via an API. Understanding their specific uses is key to designing and interacting with web services effectively. This document provides practical examples for `GET`, `POST`, and `DELETE` requests.

---

## English Version

### 1. GET Request

The `GET` method is used to retrieve data from a specified resource. It should only be used to fetch data and should not have any side effects on the server's data.

* **Retrieve tomorrow's weather forecast via a weather API.**
    * **Explanation:** This is a classic read-only operation. A client sends a `GET` request to a weather API endpoint, expecting to receive weather data for a specific date (tomorrow). The API simply provides the information without altering any server-side data.
* **Receive a list of genre recommendations via a music catalog API.**
    * **Explanation:** Another example of fetching information. A client requests a list of music genre recommendations from a catalog API. The API responds with the requested list, again, without modifying any data on the server.

### 2. POST Request

The `POST` method is used to submit data to a specified resource, often resulting in a change of state on the server or the creation of a new resource.

* **Create a new playlist via a music catalog API.**
    * **Explanation:** When a user creates a new playlist, the client sends a `POST` request containing the playlist's details (e.g., name, songs) to the music catalog API. The API processes this data to create a new playlist resource on the server.
* **Submit a product review via an App Store API.**
    * **Explanation:** To add a new product review, a client sends a `POST` request with the review content (e.g., rating, text) to the App Store API. The API then stores this new review, adding a new piece of data to its system.

### 3. DELETE Request

The `DELETE` method is used to remove a specified resource. It signifies the client's intent to delete the resource identified by the URL.

* **Removal of a user comment from a blog CMS API.**
    * **Explanation:** If a user wants to delete their comment on a blog, the client application sends a `DELETE` request to the blog's Content Management System (CMS) API, specifying the unique identifier of the comment to be removed. The API then proceeds to delete that specific comment.
* **Remove a playlist from a music catalog API.**
    * **Explanation:** To delete a playlist, a client sends a `DELETE` request to the music catalog API, targeting the specific playlist by its identifier. The API then removes the designated playlist resource from the system.

---

## Versão em Português

# Métodos HTTP em Requisições de API: Exemplos

Os métodos HTTP (ou verbos) definem o tipo de ação que um cliente pretende realizar em um recurso via API. Compreender seus usos específicos é fundamental para projetar e interagir com serviços web de forma eficaz. Este documento fornece exemplos práticos para requisições `GET`, `POST` e `DELETE`.

---

## Versão em Português

### 1. Requisição GET

O método `GET` é usado para recuperar dados de um recurso especificado. Ele deve ser usado apenas para buscar dados e não deve ter nenhum efeito colateral nos dados do servidor.

* **Recupere a previsão do tempo para amanhã por meio de uma API de clima.**
    * **Explicação:** Esta é uma operação clássica de apenas leitura. Um cliente envia uma requisição `GET` para um endpoint de uma API de clima, esperando receber dados meteorológicos para uma data específica (amanhã). A API simplesmente fornece a informação sem alterar nenhum dado no servidor.
* **Receba uma lista de recomendações de gênero por meio de uma API de catálogo de músicas.**
    * **Explicação:** Outro exemplo de busca de informações. Um cliente solicita uma lista de recomendações de gêneros musicais de uma API de catálogo. A API responde com a lista solicitada, novamente, sem modificar nenhum dado no servidor.

### 2. Requisição POST

O método `POST` é usado para submeter dados a um recurso especificado, frequentemente resultando em uma mudança de estado no servidor ou na criação de um novo recurso.

* **Crie uma nova lista de reprodução por meio de uma API de catálogo de músicas.**
    * **Explicação:** Quando um usuário cria uma nova lista de reprodução, o cliente envia uma requisição `POST` contendo os detalhes da lista (ex: nome, músicas) para a API do catálogo de músicas. A API processa esses dados para criar um novo recurso de lista de reprodução no servidor.
* **Envie uma avaliação de produto por meio de uma API da App Store.**
    * **Explicação:** Para adicionar uma nova avaliação de produto, um cliente envia uma requisição `POST` com o conteúdo da avaliação (ex: classificação, texto) para a API da App Store. A API então armazena essa nova avaliação, adicionando um novo dado ao seu sistema.

### 3. Requisição DELETE

O método `DELETE` é usado para remover um recurso especificado. Ele significa a intenção do cliente de excluir o recurso identificado pela URL.

* **Remoção de um comentário de usuário de uma API CMS de blog.**
    * **Explicação:** Se um usuário deseja excluir seu comentário em um blog, o aplicativo cliente envia uma requisição `DELETE` para a API do Sistema de Gerenciamento de Conteúdo (CMS) do blog, especificando o identificador único do comentário a ser removido. A API então procede para excluir esse comentário específico.
* **Remover uma lista de reprodução de uma API de catálogo de músicas.**
    * **Explicação:** Para excluir uma lista de reprodução, um cliente envia uma requisição `DELETE` para a API do catálogo de músicas, visando a playlist específica pelo seu identificador. A API então remove o recurso de playlist designado do sistema.
 
### Example

```python
import requests

# GET - Retrieve a resource
# Used to fetch information from a server. Data is typically passed in the URL parameters.
response_get = requests.get('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)')
# print(response_get.status_code)

# POST - Create a resource
# Used to send data to the server to create a new resource.
response_post = requests.post('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)', data={"key": "value"})
# print(response_post.status_code)

# PUT - Update an existing resource
# Used to send data to the server to update an existing resource, often replacing the entire resource.
response_put = requests.put('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)', data={"key": "value"})
# print(response_put.status_code)

# DELETE - Remove a resource
# Used to request the removal of a specified resource from the server.
response_delete = requests.delete('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)')
# print(response_delete.status_code)
```

### Exemplo
```python
import requests

# GET - Recuperar um recurso
# Usado para buscar informações de um servidor. Os dados são tipicamente passados nos parâmetros da URL.
response_get = requests.get('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)')
# print(response_get.status_code)

# POST - Criar um recurso
# Usado para enviar dados ao servidor para criar um novo recurso.
response_post = requests.post('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)', data={"key": "value"})
# print(response_post.status_code)

# PUT - Atualizar um recurso existente
# Usado para enviar dados ao servidor para atualizar um recurso existente, frequentemente substituindo todo o recurso.
response_put = requests.put('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)', data={"key": "value"})
# print(response_put.status_code)

# DELETE - Remover um recurso
# Usado para solicitar a remoção de um recurso especificado do servidor.
response_delete = requests.delete('[http://350.5th-ave.com/unit/243](http://350.5th-ave.com/unit/243)')
# print(response_delete.status_code)
```

```python
import requests
response = requests.get('http://localhost:3000/movies')

# Check if the response.status_code is equal to the requests.codes value for "200 OK"
if (response.status_code == requests.codes.ok):
  print('The server responded succesfully!')
  
# Or if the request was not successful because the API did not exist
elif (response.status_code == requests.codes.not_found):
  print('Oops, that API could not be found!')
```
```python
import requests
# Make a request to the movies endpoint of the API
response = requests.get('http://localhost:3000/movies')

if (response.status_code == 200):
  print('The server responded succesfully!')
  
# Check the response status code
elif (response.status_code == requests.codes.not_found):
  print('Oops, that API could not be found!')
```

### Print de Headers of content-type(Imprimeindo o cabeçalho de content-type)
```python
import requests
response = requests.get('http://localhost:3000/lyrics')

# Print the response content-type header
print(response.headers['content-type'])
```

### Format JSON (Formato JSON)
```python
# Set the content type to application/json
headers = {'accept': 'application/json'}
response = requests.get('http://localhost:3000/lyrics', headers=headers)

# Print the response's text
print(response.text)
```

### Accept or not (Aceitar ou não)
```python
# Add a header to use in the request
headers = {"accept":"application/xml"}
response = requests.get('http://localhost:3000/lyrics', headers=headers)

# Check if the server did not accept the request
if (response.status_code == 406):
  print('The server can not respond in XML')
  
  # Print the accepted content types
  print('These are the content types the server accepts: ' + response.headers['accept'])
else:
  print(response.text)
```


# API Authentication Methods: A Security Overview (Métodos de Autenticação de API: Uma Visão Geral de Segurança)

Authenticating a client to an online service is crucial for securing APIs. Various methods exist, each with its own advantages and disadvantages regarding simplicity, scalability, and, most importantly, security. Understanding these methods helps in choosing the most appropriate one for different scenarios.

---

## English Version

### Common API Authentication Methods (from less to more secure generally)

While each method has its place, their inherent security characteristics vary significantly.

1.  **Basic Authentication**
    * **Explanation:** This is one of the simplest authentication methods. The client sends the username and password, typically Base64 encoded, in the `Authorization` header of an HTTP request.
    * **Security Aspect:** It's generally considered the *least secure* for sensitive data or public-facing APIs because credentials are sent with every request and can be easily decoded if intercepted, especially without HTTPS. It's often suitable for internal tools or services where security is handled at a different layer.

2.  **API Key/Token Authentication**
    * **Explanation:** In this method, the client includes a unique, secret key or token in the request header or as a query parameter. The server verifies this key against a list of authorized keys.
    * **Security Aspect:** More secure than Basic Authentication as it doesn't transmit raw credentials. However, API keys are static secrets, often don't expire, and can grant broad access. If compromised, they can be used indefinitely until revoked. Their security depends heavily on how well the key is kept secret and transmitted (HTTPS is a must).

3.  **JSON Web Tokens (JWT)**
    * **Explanation:** JWTs are compact, URL-safe means of representing claims (pieces of information about a user or other entity) between two parties. The token is cryptographically signed, often with a secret key, to verify its authenticity.
    * **Security Aspect:** JWTs offer improved security over static API keys. They can contain expiration times, payloads, and are tamper-proof due to signing. They are often used for stateless authentication; once issued, the server doesn't need to store session information. However, proper handling (e.g., short expiry, refresh tokens, secure storage) is crucial, as a compromised JWT can be valid until it expires.

4.  **OAuth 2.0**
    * **Explanation:** OAuth 2.0 is an authorization framework that enables an application to obtain limited access to a user's account on an HTTP service (e.g., Google, Facebook). It doesn't authenticate the user directly, but rather grants *authorization* to access resources. It's often used with OpenID Connect for full authentication.
    * **Security Aspect:** Generally considered the *most secure and flexible* for modern applications, especially when dealing with third-party clients and user data. It uses short-lived access tokens and refresh tokens, and it explicitly separates authentication (who the user is) from authorization (what the user/application can do). Delegating access securely, without sharing user credentials directly with the client, is its main advantage.

### Security Summary:

For **public-facing applications and services handling sensitive user data**, **OAuth 2.0 (often combined with OpenID Connect)** and **JWTs (used as bearer tokens within OAuth flows)** offer the highest levels of security due to their flexibility, expiration mechanisms, and focus on delegated authorization. **API Keys** are suitable for less sensitive API access or server-to-server communication where the key can be kept highly secure. **Basic Authentication** should generally be avoided unless secured by other means (like a VPN or very strict firewall rules) or for very low-risk internal applications.

---

## Versão em Português

# Métodos de Autenticação de API: Uma Visão Geral de Segurança

Autenticar um cliente em um serviço online é crucial para proteger as APIs. Vários métodos existem, cada um com suas próprias vantagens e desvantagens em relação à simplicidade, escalabilidade e, o mais importante, segurança. Compreender esses métodos ajuda a escolher o mais apropriado para diferentes cenários.

---

## Versão em Português

### Métodos Comuns de Autenticação de API (do menos para o mais seguro, geralmente)

Embora cada método tenha seu lugar, suas características de segurança inerentes variam significativamente.

1.  **Autenticação Básica**
    * **Explicação:** Este é um dos métodos de autenticação mais simples. O cliente envia o nome de usuário e a senha, tipicamente codificados em Base64, no cabeçalho `Authorization` de uma requisição HTTP.
    * **Aspecto de Segurança:** É geralmente considerado o *menos seguro* para dados sensíveis ou APIs voltadas para o público, pois as credenciais são enviadas a cada requisição e podem ser facilmente decodificadas se interceptadas, especialmente sem HTTPS. Frequentemente é adequado para ferramentas internas ou serviços onde a segurança é tratada em outra camada.

2.  **Autenticação de Chave/Token de API**
    * **Explicação:** Neste método, o cliente inclui uma chave ou token secreto e único no cabeçalho da requisição ou como um parâmetro de consulta. O servidor verifica esta chave em relação a uma lista de chaves autorizadas.
    * **Aspecto de Segurança:** Mais seguro que a Autenticação Básica, pois não transmite credenciais brutas. No entanto, as chaves de API são segredos estáticos, muitas vezes não expiram, e podem conceder acesso amplo. Se comprometidas, podem ser usadas indefinidamente até serem revogadas. Sua segurança depende muito de quão bem a chave é mantida em segredo e transmitida (HTTPS é obrigatório).

3.  **Tokens Web JSON (JWT)**
    * **Explicação:** JWTs são meios compactos e seguros para URL de representar reivindicações (pedaços de informação sobre um usuário ou outra entidade) entre duas partes. O token é criptograficamente assinado, frequentemente com uma chave secreta, para verificar sua autenticidade.
    * **Aspecto de Segurança:** JWTs oferecem segurança aprimorada em relação às chaves de API estáticas. Eles podem conter tempos de expiração, payloads e são à prova de adulteração devido à assinatura. São frequentemente usados para autenticação sem estado; uma vez emitido, o servidor não precisa armazenar informações de sessão. No entanto, o manuseio adequado (ex: expiração curta, tokens de atualização, armazenamento seguro) é crucial, pois um JWT comprometido pode ser válido até sua expiração.

4.  **OAuth 2.0**
    * **Explicação:** OAuth 2.0 é um framework de autorização que permite a uma aplicação obter acesso limitado à conta de um usuário em um serviço HTTP (ex: Google, Facebook). Ele não autentica o usuário diretamente, mas sim concede *autorização* para acessar recursos. É frequentemente usado com o OpenID Connect para autenticação completa.
    * **Aspecto de Segurança:** Geralmente considerado o *mais seguro e flexível* para aplicações modernas, especialmente ao lidar com clientes de terceiros e dados de usuário. Ele usa tokens de acesso de curta duração e tokens de atualização, e separa explicitamente a autenticação (quem é o usuário) da autorização (o que o usuário/aplicação pode fazer). Delegar acesso de forma segura, sem compartilhar credenciais do usuário diretamente com o cliente, é sua principal vantagem.

### Resumo de Segurança:

Para **aplicações e serviços voltados ao público que lidam com dados sensíveis do usuário**, **OAuth 2.0 (frequentemente combinado com OpenID Connect)** e **JWTs (usados como bearer tokens em fluxos OAuth)** oferecem os mais altos níveis de segurança devido à sua flexibilidade, mecanismos de expiração e foco na autorização delegada. As **Chaves de API** são adequadas para acesso menos sensível à API ou comunicação servidor-para-servidor onde a chave pode ser mantida em alta segurança. A **Autenticação Básica** deve geralmente ser evitada, a menos que seja protegida por outros meios (como uma VPN ou regras de firewall muito estritas) ou para aplicações internas de risco muito baixo.

### Auth (Autenticação)
```python
# Create a headers dictionary containing and set the API key using the correct key and value 
headers = {'Authorization': 'Bearer SUA_CHAVE_AQUI'}
# Add the headers dictionary to the requests.get() call using the correct function argument
response = requests.get('http://localhost:3000/albums', headers=headers)

if(response.status_code == 200):
    print("Success!")
elif(response.status_code == 401):
    print('Authentication failed')
else:
    print('Another error occurred')
```

### Import JSON(Importando JSON)
```python
import json
album = {'id': 42, 'title':"Back in Black"}
string = json.dumps(album) # Encodes a python object to a JSON string
album = json.loads(string) # Decodes a JSON string to a Python object
```

### Request JSON (Requisitando JSON)

```python
# GET request with an accept header
response = requests.get('http://api.music-catalog.com/lyrics', headers={'accept': 'application/json'})
# Print the JSON text
print(response.text)
# Decode into a Python object
data = response.json()
```

### Sending JSON (Mandando JSON)

```python
import requests
playlist = {"name": "Road trip", "genre":"rock", "private":"true"}
# Add the playlist using via the `json` argument
response = requests.post("http://api.music-catalog.com/playlists", json=playlist)

# Get the request object
request = response.request
# Print the request content-type header
print(request.headers['content-type'])
```

### Request JSON (Requisitando JSON)

``` python
headers = {
    'Authorization': 'Bearer ' + API_TOKEN,
    # Add a header to request JSON formatted data
    "Accept": "application/json"
}
response = requests.get('http://localhost:3000/albums/1/', headers=headers)

# Get the JSON data as a Python object from the response object
album = response.json()

# Print the album title
print(album['Title'])
```
