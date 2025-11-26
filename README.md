## 📌 Descrição do Projeto

Este projeto apresenta um fluxo completo de **ETL** (Extração, Transformação e Carga) e análise de dados para uma base de vendas fictícia da **Contoso**, com a criação de um **dashboard interativo no Looker Studio**.
O objetivo é demonstrar o processo de **tratamento, modelagem e visualização de dados** para apoiar decisões de negócio, explorando métricas como faturamento, quantidade vendida, lucro e desempenho por produto, loja e período.


## Processo ETL

O fluxo de ETL é executado no **notebook**:

1. **Extração**
   Carregamento dos dados brutos (CSV’s da Contoso) para o ambiente de análise.

2. **Transformação**

   * Limpeza de dados (remoção de inconsistências e valores nulos)
   * Conversão de tipos
   * Criação de colunas derivadas (ano, mês, margens etc.)
   * Junção das tabelas dimensão com a tabela fato

## Visualização

O dashboard foi construído no **Looker Studio** e apresenta:

* **Visão Geral das Vendas**
* Faturamento por período
* Produtos mais vendidos
* Desempenho por loja e região
* Margem de lucro e análise de rentabilidade

A versão em PDF do dashboard está disponível no arquivo [`dashboard.pdf`](dashboard.pdf).


## 🎛 Tecnologias Utilizadas

* **Python** (pandas, numpy)
* **SQL** (view de agregação)
* **Google Looker Studio**
* **Jupyter Notebook**

## 👨‍💻 Autor

**Vitor Hugo Muniz de Sousa Santos**

📧 [vitormunnizzdev@gmail.com](mailto:vitormunnizzdev@gmail.com)
🌐 [www.linkedin.com/in/vitormunnizz](https://www.linkedin.com/in/vitormunnizz)

## 📝 Licença

Este projeto está licenciado sob a **MIT License**.
Sinta-se livre para usar e modificar conforme necessário, mantendo os créditos ao autor.

⭐ **Se este projeto te ajudou, deixe uma estrela no repositório!**```
