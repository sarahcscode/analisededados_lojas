
# 📊 Análise de Vendas - Challenge Data Science (Alura)

Este repositório contém um notebook em Python que realiza a ingestão e análise exploratória de dados de vendas de quatro lojas distintas. Os dados são fornecidos em formato CSV e hospedados publicamente no GitHub da Alura.

## 🔗 Fontes dos Dados

Os dados utilizados neste projeto foram coletados a partir dos seguintes arquivos:

- [loja_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- [loja_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- [loja_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- [loja_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

## 📥 Leitura dos Dados

A leitura dos arquivos é feita diretamente a partir das URLs usando o pandas:

```python
import pandas as pd

# URLs dos arquivos CSV
url1 = "URL da loja 1"
url2 = "URL da loja 2"
url3 = "URL da loja 3"
url4 = "URL da loja 4"

# Carregando os arquivos em DataFrames
loja1 = pd.read_csv(url1)
loja2 = pd.read_csv(url2)
loja3 = pd.read_csv(url3)
loja4 = pd.read_csv(url4)
````

## 🧪 Próximas Etapas (sugestões de análise)

* Unificação dos dados em um único DataFrame
* Cálculo de faturamento total por loja e por produto
* Identificação do produto mais vendido
* Média de avaliação por loja
* Análise temporal de compras
* Geração de gráficos com matplotlib ou seaborn

## 📁 Estrutura esperada dos dados

| Produto | Categoria do Produto | Preço | Frete | Data da Compra | Vendedor | Local da compra | Avaliação da compra | Tipo de pagamento | Quantidade de parcelas | lat | lon |
| ------- | -------------------- | ----- | ----- | -------------- | -------- | --------------- | ------------------- | ----------------- | ---------------------- | --- | --- |

## 💡 Requisitos

* Python 3.x
* pandas

---

Feito com 💙 por Sarah 

```

