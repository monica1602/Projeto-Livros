# Projeto-Livros

## Descrição do Projeto
Este projeto tem como objetivo desenvolver uma análise de dados voltada para um sistema de recomendação de livros, no qual o leitor pode informar o nome de um livro e/ou características desejadas (como avaliação, popularidade ou outros critérios definidos). A partir dessas informações, o aplicativo ou site utiliza códigos e consultas sobre a base de dados para retornar uma lista de livros recomendados, alinhados às preferências do usuário. O foco do projeto é transformar dados brutos do mercado editorial em recomendações práticas e personalizadas, simulando o funcionamento real de produto digital. A análise considera atributos relevantes dos livros e o comportamento dos leitores, permitindo gerar sugestões que agreguem valor à experiência do usuário.

## As tarefas são:
- Exploração inicial dos dados: Compreesão da estrutura do conjunto de dados de livros, com análise das colunas e tipos de informação disponíveis.
- Criação do dicionário de  dados: Documentação detalhada das colunas, significados e tipos de variáveis para facilitar o uso posterior.
- Tratamento dos dados: Limpeza e organização para garantir que os dados possam ser usados de forma consistente nos critérios de recomendação.
- Desenvolvimento de filtros e critérios: Construção de regras que permitam selecionar livros com base nas preferências do usuário.
- Geração de lista recomendada: Criação de códigos e consultas que retornam os livros que mais se aproximam das características desejadas pelo leitor.

## Dicionário de Dados
- Título.
- Autor.
- Número de páginas.
- Gênero.
- Ano de lançamento.
- Média de avaliações.
- Número de avaliações.
- Editora.

## Ferramentas e Biliotecas utilizadas
- Python: A principal linguagem utilizada para a análise de dados devido à sua flexibilidade e ampla gama de bibliotecas para análsie e visualização de dados. Python é uma escolha popular devido à sua facilidade de uso e suporte a diversas bibliotecas especializadas.
- Pandas: Biblioteca fundamental para manipulação e análise de dados. Pandas permite a organização, limpeza, transformação e análise de dados de forma eficiente, trabalhando com estruturas como DataFrames que facilitam o manuseio de grandes volumes de dados.
- Matplotlib: Biblioteca usada para criar gráficos em Python. Matplotlib é versátil e permite a criação de gráficos estáticos, interativos e animados, sendo essencial para a visualização de dados e para a geração de gráficos personalziavéis.
- Seaborn: Biblioteca baseada no Matplotlib, mas com recursos adicionais para facilitar a criação de gráficos mais complexos e atraentes. Seaborn é usado para visualização de dados estatísticas, proporcionando gráficos com uma aparência mais refinada e integração direta com Pandas.

## Imagens

### Gráfico Ano de Lançamento
<img width="500" height="562" alt="grafico ano de lançamento" src="https://github.com/user-attachments/assets/e2fdefb4-2654-4d21-954e-774c3182c0b3" />

### Gráfico Faixa de Páginas
<img width="500" height="600" alt="grafico faixa de paginas" src="https://github.com/user-attachments/assets/59b48671-3320-4b9e-93ff-e2777501f217" />

### Gráfico Lançamentos por Ano
<img width="500" height="597" alt="grafico lançamentos por ano" src="https://github.com/user-attachments/assets/03245237-7147-4cc0-8799-371d0a08471a" />

### Gráfico Média de Avaliações
<img width="500" height="598" alt="grafico media de avaliações" src="https://github.com/user-attachments/assets/1906c808-73a3-4729-9367-b038118cc285" />

### Histograma Gênero
<img width="500" height="632" alt="histograma genero" src="https://github.com/user-attachments/assets/5ab18c27-0e40-43cd-b44b-1bfac5e1b52d" />

### Tabela Autores
<img width="272" height="392" alt="tabela autores" src="https://github.com/user-attachments/assets/578b6022-bc23-4f83-a7ac-3c23d08dcddb" />

### Tabela Editoras
<img width="305" height="388" alt="tabela editoras" src="https://github.com/user-attachments/assets/4ac6c15e-c3b4-4586-8500-4d92080ed7ae" />

### Tabela Faixa de Páginas
<img width="273" height="247" alt="tabela faixa de paginas" src="https://github.com/user-attachments/assets/a9b4b3c5-bb09-454a-92eb-2ffe335048ff" />

### Tabela Lista 1
<img width="1281" height="217" alt="tabela lista 1" src="https://github.com/user-attachments/assets/83f822b1-836a-4623-a519-99cfe8cc4154" />

### Tabela Lista 2
<img width="1235" height="216" alt="tabela lista 2" src="https://github.com/user-attachments/assets/de61ad53-c49f-4a26-88cd-834a88bfb311" />

### Tabela Lista 3
<img width="1241" height="218" alt="tabela lista 3" src="https://github.com/user-attachments/assets/365045e1-7605-4782-8065-256c5fcd1118" />

### Tabela Lista 4
<img width="1228" height="390" alt="tabela lista 4" src="https://github.com/user-attachments/assets/d721693e-c54a-4167-8770-9bb1be0cea73" />

### Tabela Lista 5
<img width="1252" height="397" alt="tabela lista 5" src="https://github.com/user-attachments/assets/16943931-8f8c-4342-953b-a97109f94d52" />

### Tabela Lista 7
<img width="1401" height="568" alt="tabela lista 7" src="https://github.com/user-attachments/assets/40d03251-1553-4a03-8d35-6d522e6d0584" />

### Tabela Lista Específica 1
<img width="1272" height="207" alt="tabela lista especifica 1" src="https://github.com/user-attachments/assets/749a791c-efcb-412d-a569-020769335756" />

### Tabela Lista Específica 2
<img width="1398" height="572" alt="tabela lista especifica 2" src="https://github.com/user-attachments/assets/5130f1fe-3a17-428c-a635-ce4b5587ad01" />


## Resultados
- Geração de uma lista de livros recomendados: construída a partir de critérios definidos pelo próprio usuário no momento da busca. Essa lista é resultado da aplicação de filtros e regras sobre a base de dados, simulando o funcionamento de um sistema de recomendação em um aplicativo ou site voltado para leitores.
- Avaliação média: utilizada para identificar livros com melhor aceitação entre os leitores, priorizando obras bem avaliadas e que tendem a oferecer uma experiência de leitura mais satisfatória.
- Popularidade (número de avaliações): considerado como um indicativo de confiabilidade e relevância, destacando livros com maior volume de avaliações e maior consenso da comunidade de leitores.
- Características escolhidas pelo leitor: incluem critérios definidos pelo usuário, como gênero, similaridade com um livro de referência ou outros atributos disponíveis na base de dados, permitindo refinar os resultados e gerar recomendações mais alinhadas às preferências individuais.
- Gênero com  maior quantidade de título: a análise também também permitiu identificar os gêneros mais representados na base de dados, ou seja, aqueles que possuem maior número de livros disponíveis. Esse resultado ajuda a entender tendências do catálogo, apontando categorias com maior diversidade de obras e maior potencial para recomendações, além de apoiar decisões estratégicas sobre foco de conteúdo e segmentação de leitores.

## Aprendizados
- Compreensão e estruturação do problema: o projeto reforçou a importância de entender o problema antes da análise, traduzindo a necessidade de recomendação de livros em critérios claros e mensuravéis dentro da base de dados.
- Organização e documentação dos dados: a criação do dicionário de dados mostrou-se fundamental para garantir clareza, consistência e confiabilidade durante toda a análsie, facilitando tanto o desenvolvimento quanto futuras manutenções do projeto.
- Aplicação de filtros e critérios de recomendação: foi possível aprender como transformar preferências subjetivas dos usuários, como gostos e interesses, em regras técnicas, utilizando filtros e condições que tornam a recomendaçãomais objetiva e reproduzível.
- Análise orientada à experiência do usuário: o projeto destacou a importância de gerar resultados que façam sentido para o usuário final, indo além da análise técnica e considerenado como os dados podem apoiar escolhas reais de leitura.
- Transformação de dados em insights práticos: ao longo do desenvolvimento, ficou evidente como dados brutos podem ser organizados e analisados para gerar informações úteis.

## Contexto Real
- Aplicação em produtos digitais: o projeto simula o funcionamento de um sistema de recomendação presente em aplicativos e sites voltados a leitores, onde a personalização do conteúdo é um diferencial importante para a experiência do usuário.
- Personalização da experiência: sistemas de recomendações permitem sugerir livros de acordo com preferências individuais, histórico ou critérios definidos pelo usuário, tornando a navegação mais instrutiva e relevante.
- Aumento de engajamento e retenção: ao facilitar a descoberta de novos livros alinhados aos interesses do leitor, esse tipo de sistema contribui para maior tempo de uso da plataforma e maior engajamento dos usuários.
- Apoio à tomada de decisão: as recomendações geradas a partir de dados ajudam usuários a escolher leituras com mais confiança, além de apoiar estratégias de negócio relacionadas a curadoria de conteúdo e destaque de títulos.
- Escabilidade e evolução do produto: a lógica de recomendação desenvolvida no projeto pode ser expandida e adaptada para novos critérios, maior volume de dados ou integração com modelos mais avançados, refletindo desafios reais do mercado.

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal








