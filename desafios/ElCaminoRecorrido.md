# Desafíos de NLP – FIUBA / CEIA

> De contar palabras a traducir oraciones completas, paso a paso en cuatro notebooks.

Este repositorio reúne las entregas de los **Desafíos 1, 2, 3 y 4** de la materia  
**Procesamiento de Lenguaje Natural (FIUBA – CEIA)**.  
La idea es mostrar, de forma incremental, cómo pasamos de enfoques “clásicos” de NLP  
a modelos neuronales de traducción.

---

## 🗂 Contenido del repositorio

### 🧩 Desafío 1 – Representaciones clásicas y clasificación de textos  
`Desafio_1-Rodrigues da Cruz.ipynb`  

- Carga y exploración del dataset de *20 Newsgroups*.  
- Vectorización de textos con **BoW** y **TF-IDF**.  
- Entrenamiento de modelos de clasificación de documentos.  
- Análisis de similitud entre documentos y términos.

---

### 🎵 Desafío 2 – Word embeddings sobre letras de canciones  
`Desafio_2_Rodrigues_da_Cruz (1).ipynb`  

- Entrenamiento de un modelo **Word2Vec** sobre letras (ej. Bob Dylan).  
- Búsqueda de palabras similares y casos de “la que no encaja”.  
- Reducción de dimensión y visualización del espacio de palabras.  
- Interpretación de grupos semánticos en el embedding.

---

### ✍️ Desafío 3 – Modelo de lenguaje a nivel caracter  
`Desafio_3_Rodrigues_da_Cruz.ipynb`  

- Preparación de un corpus a nivel caracter para predicción del siguiente símbolo.  
- Construcción de un modelo recurrente (Embedding + LSTM).  
- Generación de texto variando la temperatura para analizar creatividad vs. coherencia.  
- Comentarios sobre el comportamiento del modelo y sus límites.

---

### 🌍 Desafío 4 – Traducción automática (es → en)  
`Desafio_4_Rodrigues_da_Cruz.ipynb`  

- Uso de un corpus de pares de oraciones español–inglés (tipo Anki deck).  
- Limpieza, tokenización y armado de secuencias para encoder–decoder.  
- Implementación de un modelo de **traducción neuronal** (seq2seq).  
- Evaluación cualitativa de traducciones en oraciones no vistas.

---

## ⚙️ Cómo ejecutar los notebooks

1. Crear y activar un entorno de Python (3.10+ recomendado).
2. Instalar las dependencias principales (ejemplo):

   ```bash
   pip install scikit-learn gensim nltk torch matplotlib pandas seaborn
