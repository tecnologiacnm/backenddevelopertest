# DESENVOLVEDOR BACKEND - TESTE

- [DESENVOLVEDOR BACKEND - TESTE](#desenvolvedor-backend---teste)
    - [DESAFIO](#desafio)
      - [Stories:](#stories)
    - [ESPECIFICAÇÕES](#especificações)
      - [_Se precisar escrever, comece a partir daqui..._](#se-precisar-escrever-comece-a-partir-daqui)


Este teste tem como objetivo testar seus conhecimentos e tempo de entrega da atividade.

### DESAFIO
O desafio é criar uma api em NestJS para portal de anúncios. Seguir com as rotas conforme as seguintes histórias

#### Stories:

+ Como cliente quero listar as propostas enviadas pelos usuários (nome, tipo de proposta, telefone, email e data de envio).

+ Como cliente quero visualizar as propostas enviadas pelos usuários (nome, titulo do anuncio, valores, tipo de proposta, telefone, email e data de envio).

+ Como cliente gostaria de poder filtrar minhas propostas por tipo, período, pelo status da proposta(NEW, ANSWERED, OPENED, FILED).

+ Como usuário quero poder enviar propostas para os anúncios.

+ Este fluxo pode gerar muitas requisições por segundo em questão de ser um portal de anúncio.

+ Caso anúncio não esteja ativo, não é possível enviar propostas para o mesmo.

### ESPECIFICAÇÕES
* Os tipos de propostas são: 
    * Financiamento(1)
        * nome
        * email
        * telefone
    * Mensagem(2)
        * nome
        * email
        * telefone
        * mensagem enviada pelo usuário

* Para listagem das propostas, não é para consultar o banco de dados.

* Não precisa se preocupar com autenticação, mas sempre que for realizado uma busca das propostas, só pode retornar do próprio cliente.

_Utilizando SQlite e TypeORM crie um banco de dados seguindo o exemplo do db.json. Existe um cliente com anúncio e proposta para exemplo._

~~~~
~~~~
#### _Se precisar escrever, comece a partir daqui..._
