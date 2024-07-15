# Análise de Preferências de Compras no Shopping: Insights Estratégicos para Aumento de Lucros

![Static Badge](https://img.shields.io/badge/python-%233776AB?style=for-the-badge&logo=python&logoColor=white)
![Static Badge](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Static Badge](https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white)
![Static Badge](https://img.shields.io/badge/matplotlib-%23135F9B?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/seaborn-%23444876?style=for-the-badge)

Esta análise visa extrair insights valiosos sobre a preferência das pessoas durante as compras com base em alguns dados históricos que serão cruciais para orientar o planejamento estratégico do shopping, permitindo ajustes precisos na oferta de produtos e serviços para maximizar a satisfação do cliente e, consequentemente, aumentar a rentabilidade.

# Descrição do Dataset:

Conjunto de dados: [disponível no Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

Glossário do conjunto de dados:

* `Customer ID` -  Identificador único para cada cliente.
* `Age` - Idade do cliente.
* `Gender` - Sexo do cliente (Masculino/Feminino).
* `Item Purchased` - O item comprado pelo cliente.
* `Category`- Categoria do item comprado.
* `Purchase Amount (USD`- O valor da compra em USD.
* `Location`- Localização onde a compra foi efectuada.
* `Size`- Tamanho do item comprado.
* `Color`- Cor do item comprado.
* `Season`- Estação durante a qual a compra foi efectuada.
* `Review Rating`- Classificação dada pelo cliente para o item comprado.
* `Subscription Status`- Indica se o cliente tem uma subscrição (Sim/Não).
* `Shipping Type`- Tipo de envio escolhido pelo cliente.
* `Discount Applied`- Indica se foi aplicado um desconto à compra (Sim/Não).
* `Promo Code Used` - indica se foi utilizado um código promocional para a compra (Sim/Não).
* `Previous Purchases`- O número total de transacções concluídas pelo cliente na loja, excluindo a transação em curso.
* `Payment Method`- O método de pagamento preferido do cliente.
* `Frequency of Purchases`- Frequência com que o cliente efectua compras (por exemplo, semanal, quinzenal, mensal).

# Etapas do Projeto:

* **Conhecendo o Dataset**: Importação das bibliotecas necessárias e leitura do conjunto de dados.
* **Análises Preliminares**: Exploração inicial dos dados, com o objetivo de responder perguntas e obter insights importantes.
* **Visualização dos Dados**: Utilização de gráficos de boxplot e histograma para entender a distribuição dos dados e identificar possíveis outliers. Também plotagem de gráficos de dispersão para observar as relações entre as variáveis.

# Análise Exploratória dos Dados

### 1. Distribuição de Idade

![img](imagens/01.png)

- A maioria das pessoas que fazem compras pertence a faixa etária 20-60.

---

### 2. Distribuição por Gênero

![img](imagens/02.png)

- O maior número de compras é realizado por homens.

---

### 3. Itens mais comprados

![img](imagens/03.png)

- Blusa é o item mais comprado, seguido de Jóias e Calças.

---

### 4. Compras por Estação

![img](imagens/04.png)

- As pessoas fazem as suas compras sobretudo na primavera e no outono.

---

### 5. Distribuição por Localização

![img](imagens/05.png)

- A maioria das pessoas prefere fazer compras no ponto de venda "Montana", seguido do ponto de venda "Califórnia.

### 6. Método de Pagamento Preferido

![img](imagens/06.png)

- "PayPal" é o método mais preferido, seguido de "cartão de crédito" e "dinheiro".

---

### 7. Distribuição da Frequência de Compras

![img](imagens/07.png)

- A maioria das pessoas prefere fazer compras de "A cada 3 meses', seguido de "Anualmente".

---

### 8. Uso de cupom de desconto

![img](imagens/08.png)

- A maioria das pessoas faz compras sem utilizar cupom de desconto.

---

### 9. Tipo de Envio Preferido

![img](imagens/09.png)

- A maioria das pessoas opta por "Envio gratuito", seguido de "Padrão" e "Retirar na loja".

---

### 10. Média de avaliações por gênero

![img](imagens/10.png)

- A média de avaliações dos homens é maior que a média de avaliações das mulheres.

---

### 11. Preferência de Cor

![img](imagens/11.png)

- A maioria das pessoas compra roupa de cor "Oliva", seguida de "Amarelo" e "Prateado".

---

### 12. Categoria por Gênero e Método de Pagamento

![img](imagens/12.png)

- A maioria das compras é feita por homens.
- A maioria dos homens compra roupa e acessórios.
- A maioria efectua o pagamento com cartão de crédito.



