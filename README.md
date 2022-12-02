# Escolha-Sistema-NOSQL
Neste Projeto chamado "você não gosta de relacionamentos" proposto pelo meu professor tive que escolher um sistema de gerenciamento NOSQL para resolver o problem proposto



## Desafios propostos

Escolher o Sistema
Dentro de uma empresa existem dados sensíveis que requerem um maior cuidado de quem tem acesso e pode manipulá-los. Os sistemas de gerenciamento de identidade e acesso armazenam informações sobre as pessoas de uma empresa (nome, cargo, função e nível de acesso) e também sobre os dados (onde estão contidos, quais flags têm, qual o tipo de dado, entre outros), juntamente com as regras que regem o acesso a esses recursos.



Você trabalha como analista de dados em uma empresa que desenvolve softwares relacionados à área de gestão de pessoas. A empresa está desenvolvendo uma nova versão do software e você foi convidado a ajudar na escolha de um banco de dados NoSQL para esta solução.



Levando em consideração que o acesso a esse tipo de documento ​​​​​​​deve ser rápido e garantir que o usuário tenha seguido todas as regras determinadas, qual seria o melhor tipo de sistema de banco de dados entre documento, chave-valor, grafos e colunas para essa situação?




## Solução Proposta

De acordo com o os requisitos que temos na empresa precisamos armazenar nomes de pessoas, cargo e função, pois precisaremos fazer uma consulta desses dados depois e além de visualizar as informações dessas pessoas, temos que visualizar os tipos de dados. Então depois da minha pesquisa, defini para que usaremos o sistema NOSQL em forma de documentos, porque esse sistema armazena e construí um arquivo do tipo JSON com os dados, o que facilita em uma busca por qualquer pessoa ou tipo de dados, como podemos armazenar diversas pessoas nesse sistema cada documento pode catalogar cada uma.

Exemplo de arquivo de JSON utilizando livros


[
    {
        "year" : 2013,
        "title" : "Turn It Down, Or Else!",
        "info" : {
            "directors" : [ "Alice Smith", "Bob Jones"],
            "release_date" : "2013-01-18T00:00:00Z",
            "rating" : 6.2,
            "genres" : ["Comedy", "Drama"],
            "image_url" : "http://ia.media-imdb.com/images/N/O9ERWAU7FS797AJ7LU8HN09AMUP908RLlo5JF90EWR7LJKQ7@@._V1_SX400_.jpg",
            "plot" : "A rock band plays their music at high volumes, annoying the neighbors.",
            "actors" : ["David Matthewman", "Jonathan G. Neff"]
        }
    },
    {
        "year": 2015,
        "title": "The Big New Movie",
        "info": {
            "plot": "Nothing happens at all.",
            "rating": 0
        }
    }
]




Neste exemplo o arquivo JSON esta catalogando livros podemos observar que cataloga os tipos dedados e informações a respeito dos livros podemos fazer o mesmo com as pessoas.
