# Proyecto: Análisis de Texto con NLP

## 📌 Descripción
Detectando similitud y términos clave en textos clínicos breves  

## 🎯 Objetivos
Aplicar un pipeline de procesamiento de texto con SpaCy, NLTK y TfindfVectorizer, evaluando su
impacto en la calidad de los datos y preparación para tareas de clasificación o agrupación.

## 🛠️ Tecnologías utilizadas
- Python (NLTK, spaCy, Scikit-Learn, Matplotlib, WordCloud, pandas y re)
- Jupyter Notebook

## 📂 Código fuente
- Notebooks: [`notebooks/`](notebooks/)

## 📊 Resultados
- El preprocesamiento genera un corpus más compacto y semánticamente más informativo, lo que facilita la representación y el análisis posterior de los textos clínicos.
- El preprocesamiento redujo el tamaño del vocabulario al eliminar stopwords, signos y variaciones morfológicas, dejando un conjunto más limpio.
- La longitud promedio de los documentos disminuyó, lo que refleja que ahora se conservan principalmente los términos más relevantes y representativos.
- La vectorización con TF-IDF permitió identificar de forma clara las palabras clave en cada nota clínica, resaltando síntomas y diagnósticos distintivos.
- Este pipeline de limpieza + lematización + vectorización facilita tareas posteriores como clasificación o clustering, ya que entrega un corpus más compacto, normalizado y libre de ruido.

## 🤔 Reflexión personal
Me permitió profundizar en el preprocesamiento de texto, tokenización y embeddings para mejorar la calidad de los modelos.
