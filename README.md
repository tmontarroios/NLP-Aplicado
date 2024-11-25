# nlp_aplicado
Linguagem Natural Aplicada
# Classificação de Gêneros de Filmes com Descrições de Tramas  

Este projeto utiliza técnicas de **Processamento de Linguagem Natural (NLP)** e **Aprendizado de Máquina (ML)** para prever o gênero de filmes a partir de suas descrições de trama. O objetivo é transformar descrições textuais em representações compreensíveis por modelos de machine learning e avaliar o desempenho de diferentes abordagens para a tarefa de classificação.

## 📁 Dataset  
- **Nome**: [Wikipedia Movie Plots](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots/data)  
- **Tamanho**: 34.886 filmes  
- **Informações Utilizadas**:  
  - **Plot**: Descrição longa da trama do filme.  
  - **Genre**: Gênero(s) do filme.  

---

## 🚀 Etapas do Projeto  

### 1. **Limpeza e Pré-Processamento dos Dados**  
Técnicas aplicadas:  
- **Tokenização**: Divisão do texto em unidades significativas (tokens).  
- **Remoção de StopWords**: Eliminação de palavras comuns que não contribuem significativamente para a análise (ex.: "o", "de", "é").  
- **Lematização**: Redução de palavras à sua forma base (ex.: "correu" → "correr").  

### 2. **Extração de Características**  
Métodos explorados para transformar os textos em vetores numéricos:  
- **Bag of Words (BoW)**  
- **TF-IDF (Term Frequency-Inverse Document Frequency)**  
- **Embeddings Tradicionais**: GloVe  
- **Doc2Vec**  
- **Embeddings Pré-Treinados**: Modelos mais robustos para capturar semântica textual.  

### 3. **Treinamento de Modelos de Classificação**  
Algoritmos testados:  
- **MLP (Perceptron Multicamadas)**  
- **LSTM (Long Short-Term Memory)**  
- **BERT/Transformers**  

### 4. **Avaliação do Desempenho**  
Métricas utilizadas:  
- **Acurácia**  
- **Precisão**  
- **Recall**  
- **Matriz de Confusão**  

---

## 📊 Objetivo  
O objetivo principal é comparar o desempenho das abordagens e identificar quais modelos são mais eficientes para classificar gêneros de filmes com base em suas descrições textuais.  

---

## 🔧 Tecnologias Utilizadas  
- **Python**  
  - Bibliotecas: `nltk`, `scikit-learn`, `TensorFlow`, `Keras`

---

## 🛠️ Configuração do Ambiente  

### 1. Criando um ambiente virtual  (No Linux) 
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## 📚 Referências  
- Dataset original: [Wikipedia Movie Plots](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots/data)  
- Artigos e documentações sobre técnicas de NLP e ML.  

---

