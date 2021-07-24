# Desafio Backend

Desafio para candidatos à vaga de Software Engineer Backend para o time de Software Enginering da Wevo - o primerio iPaaS da América Latina. A ideia é que você aprenda, se divirta, e mostre o seu melhor nesse desafio.

## O que será analisado?
1. Resolução do problema proposto.
2. Escrita e estrutura de código, design e estruturação do projeto e boas práticas de desenvolvimento.
3. Commits organizados e bem descritos.
4. Build e correto funcionamento do projeto.

## Como deve ser feito?
1. Você pode desenvolver o desafio em NodeJS ou C# (o que fizer você se sentir mais confortável).
2. Você pode utilizar qualquer lib/pacore terceira (NPM ou Nuget) que achar necessário - nós não costumamos reinventar a roda.
3. Deixa claro todos os passos para rodar o projeto.
4. Faça da melhor maneira possível na qual possamos ter visibilidade do seu conhecimento e também para que possamos sentir confiança em seu código (não se preocupe se, nesse momento, seu projeto ficar "muito inflado" para o problema em questão). Nós queremos ter visibilidade do que você realmente conheçe.

## Como entregar o desafio?
1. Realize um `fork` desse repositório e realizar as alterações que forem necessárias.
2. Após concluir o desafio, realize um `pull-request` para esse repositório e notifique o nosso time de Gente & Gestão.

## O desafio:
### Entrega obrigatória:
Realizar o desenvolvimento de uma API responsável por realizar as operações de CRUD (Create, Read, Update e Delete) em uma entidade `pessoa` contendo os campos listados abaixo. Deve-se aplicar as regras de negócio necessária para garantir a integridade das informações à serem processadas, por exemplo: validar duplicidade de dados cadastrais, dados nos formatos e máscaras corretos, alteração/remoção de registros inexistentes e etc. A gestão das informações deve ser feita de duas formas:<br><br>
     - *Implementando uma interface que faz a gestão dos dados em memória durante o ciclo de vida da aplicação.*<br>
     - *Implementando uma interface que faz a gestão dos dados em um banco de dados (SQL ou No-SQL)*

A entidade pessoa deve ser composta dos seguintes campos:<br>
    - *Nome, Idade, Data de Nascimento, CPF e E-mail*
     
### Opcional:
Realizar o desenvolvimento de uma aplicação front-end utilizando implementando as APIs que foram desenvolvidas no passo acima. Caso opte por fazer essa parte complementar, é importante considerar as telas para realizar a gestão de todas as operaçÕes CRUD.

### Diferencial:
Deixar a aplicação preparadas para ser executada dentro de um container Docker.
Garantir a qualidade da entrega e funcionamento das APIs com implementação de testes automatizados.
