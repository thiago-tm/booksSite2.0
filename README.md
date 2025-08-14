# booksSite – Relatório do Projeto

No desenvolvimento do **booksSite**, eu implementei diversas funcionalidades para aprimorar a experiência do usuário e aplicar conceitos fundamentais de JavaScript.

## Carregamento e Exibição de Dados
- Carreguei o projeto base e realizei uma requisição para obter todos os livros de uma **API de exemplo**.
- Utilizei o método **forEach** para exibir os livros na tela, manipulando o DOM de forma mais elegante do que com um `for` tradicional.

## Filtragem de Livros
- Explorei o método **filter**, realizando testes na documentação oficial do JavaScript para compreender seu funcionamento.
- Implementei botões para filtrar livros por categoria e exibir apenas os disponíveis.
- Criei um botão específico para mostrar apenas livros disponíveis, exibindo a seção de **valor total** somente quando esta opção fosse selecionada.

## Cálculo e Ordenação
- Utilizei o método **reduce** para calcular o valor total de todos os livros disponíveis.
- Apliquei o método **sort** para ordenar os livros por preço.
- Melhorei a experiência visual aplicando opacidade aos livros indisponíveis.

## Manipulação de Preços
- Utilizei o método **map** para aplicar descontos nos preços de cada livro.
- Entendi a diferença entre **map** e **forEach**:  
  - **map** retorna um novo array com as transformações.  
  - **forEach** apenas executa ações sobre cada item.

## Resultado Final
O projeto apresenta:
- Filtros dinâmicos por categoria.
- Exibição condicional de informações.
- Cálculo automático do valor total dos livros disponíveis.
- Ordenação por preço.
- Melhorias visuais para facilitar a navegação do usuário.