# Projeto-Banco-de-Dados

## Programa Santander Coders 2024.1 | Turma Data Science | Ada Tech

Este projeto foi desenvolvido como parte do módulo de Banco de Dados I, curso Data Science do programa Santander Coders 2024.1.

O projeto envolve a exploração de um banco de dados de locação de DVDs para responder a perguntas utilizando SQL. O banco de dados `dvd_rental` contém 15 tabelas que modelam o funcionamento de uma loja de aluguel de DVDs. A seguir, é apresentada uma breve explicação sobre o banco de dados e, logo após, listam-se as perguntas a serem respondidas com consultas SQL.

### Consultas SQL:

1. **Quais são os filmes, suas respectivas categorias e idiomas?**
   - A consulta deve retornar o título do filme (`film.title`), o nome da categoria (`category.name`) e o idioma do filme (`language.name`).

2. **Quais foram os filmes alugados entre os dias 1 de fevereiro e 15 de março de 2006 na loja 1?**
   - A consulta deve filtrar os aluguéis (`rental.rental_date`) e a loja (`store.store_id = 1`), listando os filmes alugados no período especificado.

3. **Qual a quantidade de vezes que cada filme foi alugado?**
   - A consulta deve retornar o número de vezes que cada filme foi alugado.

4. **Para cada funcionário, qual é o valor total retornado em locações e a quantidade total de locações?**
   - A consulta deve retornar o total de locações (`payment.amount`) e a quantidade de locações (`rental.rental_id`) para cada funcionário (`staff.staff_id`).

5. **Qual é o nome de categoria de filme que nos retorna mais dinheiro no total?**
   - A consulta deve ordenar as categorias de filmes (`category.name`) pelo valor total recebido em pagamentos (`payment.amount`), listando todas as categorias, inclusive aquelas que não geraram nenhuma receita.

