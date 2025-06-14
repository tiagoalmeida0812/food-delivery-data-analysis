# Análise de Dados Aplicada a Problemas de Negócios

Este projeto foi desenvolvido como parte da disciplina **Análises Descritivas e Modelos Analíticos para Problemas de Negócios**, com o objetivo de aplicar técnicas de análise de dados, desde a carga e tratamento até a modelagem e avaliação, com foco em problemas reais de negócios.

## 📁 Estrutura do Projeto

- `Projeto.ipynb`: Notebook principal com todas as etapas do projeto
- `README.md`: Este arquivo

## 👥 Integrante

- Tiago Gonçalves de Almeida - RA 12523117709  
[LinkedIn](https://www.linkedin.com/in/tiagoalmeida-ti/)

## 📌 Etapas do Projeto

### 1. **Carregamento dos Dados**
Os dados foram carregados a partir de arquivos `.csv`, utilizando a biblioteca `pandas`.

### 2. **Transformação de Variáveis**
Foi avaliada a necessidade de transformar variáveis como idade em faixas (ex.: 18-25, 26-35, etc.).

### 3. **Codificação de Variáveis Categóricas**
Variáveis categóricas foram codificadas com `LabelEncoder` e `OneHotEncoder`, conforme o tipo e a necessidade da modelagem.

### 4. **Normalização**
Variáveis numéricas foram normalizadas utilizando `StandardScaler`.

### 5. **Balanceamento da Variável Alvo**
Quando necessário, técnicas como `SMOTE` foram aplicadas para balanceamento da variável alvo.

### 6. **Tratamento de Correlação**
Foi analisada a matriz de correlação para remoção de variáveis altamente correlacionadas.

### 7. **Seleção de Variáveis**
Técnicas como `SelectKBest` e `RandomForest` foram utilizadas para selecionar as variáveis mais relevantes.

### 8. **Modelagem**
Foi aplicado um modelo de classificação ou regressão, dependendo do problema identificado. Utilizamos busca automatizada de hiperparâmetros com `GridSearchCV`.

### 9. **Avaliação**
A avaliação do modelo foi feita com métricas adequadas:
- Classificação: `accuracy`, `precision`, `recall`, `f1-score`, e matriz de confusão
- Regressão: `RMSE`, `MAE` e gráfico de linha de saída

### 10. **Visualização dos Resultados**
Os resultados foram visualizados com:
- Matriz de confusão (para classificação)
- Gráfico de dispersão (para agrupamentos, se aplicável)
- Linha de saída (para regressão)

## 📊 Tecnologias Utilizadas

- Python 3
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn

## 📝 Instruções de Execução

1. Clonar o repositório:
   ```bash
   git clone https://github.com/usuario/repositorio.git
   ```
2. Instalar as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Executar o notebook `Projeto.ipynb`
