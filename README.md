# 🧠 Projeto IA: Previsão de Score de Crédito  

Este projeto foi desenvolvido durante a **Jornada Python da Hashtag Programação**, com o professor **Lira**, e tem como objetivo **prever o score de crédito de clientes** (Ruim, Ok, Bom) utilizando técnicas de **Machine Learning**.  

Foi um dos projetos da **aula 3 de 4**, e marcou um grande avanço na minha jornada de estudos em **Análise de Dados e Inteligência Artificial**. 🚀  

---

## 📌 Objetivo  
Criar um modelo de IA capaz de, com base nos dados dos clientes, **classificar automaticamente o score de crédito** como:  
- Ruim (Poor)  
- Ok (Standard)  
- Bom (Good)  

---

## ⚙️ Tecnologias e Ferramentas Utilizadas  

- **Python** 🐍  
- **Pandas** — tratamento e análise de dados  
- **Scikit-learn (sklearn)** — criação e treinamento de modelos de Machine Learning  
- **LabelEncoder** — conversão de variáveis categóricas em numéricas  
- **RandomForestClassifier** — modelo baseado em árvore de decisão  
- **KNeighborsClassifier (KNN)** — modelo baseado em vizinhos próximos  
- **train_test_split** — divisão da base em dados de treino e teste  
- **accuracy_score** — avaliação da acurácia dos modelos  

---

## 🧩 Etapas do Projeto  

1. **Importação e análise inicial dos dados** (`clientes.csv`)  
2. **Tratamento e preparação da base**  
   - Conversão de colunas categóricas com `LabelEncoder`  
3. **Divisão dos dados** em treino e teste  
4. **Criação e treinamento de dois modelos**  
   - Random Forest  
   - KNN  
5. **Avaliação da acurácia** dos modelos e seleção do melhor  
6. **Previsão do score de novos clientes** (`novos_clientes.csv`)  

---

## 📈 Resultados  
- O modelo com melhor desempenho foi o **Random Forest**  
- Obteve uma **alta acurácia nas previsões**  
- Foi possível prever corretamente o score de crédito de novos clientes de forma automatizada  

---

## 📊 Resultados Visuais  

### Acurácia dos Modelos
![Gráfico de Acurácia](./imagens/accuracia_modelos.png)

### Tabela de Novos Clientes com Previsões
![Tabela de Resultados](./imagens/tabela_previsoes.png)

> As imagens acima mostram a comparação de desempenho entre os modelos e o resultado final das previsões realizadas no arquivo `novos_clientes.csv`.

---

## 📂 Estrutura do Projeto  

```bash
.
├── clientes.csv
├── novos_clientes.csv
├── imagens
│   ├── accuracia_modelos.png
│   └── tabela_previsoes.png
├── main.py
└── README.md

💬 Autor

Victor dos Santos Gonçalves Peixoto
📍 Fortaleza - CE
📧 victoorsaantos16@gmail.com

🔗 LinkedIn

💻 GitHub