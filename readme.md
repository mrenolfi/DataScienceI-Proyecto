# 🧠 Proyecto Final - Parte III | Renolfi

Este repositorio contiene el desarrollo de la Parte III del Proyecto Final del curso **Data Science I (Coderhouse)**.  
El objetivo fue aplicar un modelo de Machine Learning sobre un dataset de reservas de hoteles, con foco en clasificación binaria: **cancelada vs no cancelada**.

---

## 📁 Contenido del repositorio

- `ProyectoParteIII_Renolfi.ipynb`: notebook con el análisis completo, preprocesamiento, selección de variables, entrenamiento de modelos y evaluación.
- `6_reservas_hoteles.csv`: dataset original utilizado para el análisis.
- Este archivo `README.md`.

---

## 🧪 Objetivo del análisis

El objetivo fue **predecir si una reserva será cancelada o no**, a partir de variables del comportamiento del cliente y características de la reserva.  
Este tipo de análisis es especialmente útil para **áreas de revenue management y planificación hotelera**.

---

## 🔍 Etapas del análisis

1. **Preprocesamiento de los datos**
   - Limpieza de valores nulos
   - Codificación de variables categóricas
   - Creación de nuevas variables

2. **Selección de características**
   - Se aplicó `SelectKBest` para reducir la dimensionalidad y conservar solo las variables más relevantes.

3. **Modelado**
   - Se entrenaron dos modelos de clasificación:
     - Árbol de Decisión
     - K-Nearest Neighbors (KNN)
   - Los modelos fueron evaluados con:
     - Accuracy
     - Matriz de Confusión
     - Precisión, Recall y F1-Score

4. **Evaluación y comparación**
   - Se comparó el rendimiento de ambos modelos.
   - Se discutieron ventajas, limitaciones y posibles mejoras.

---

## 📌 Conclusiones

- Ambos modelos alcanzaron niveles razonables de precisión.
- El **Árbol de Decisión** mostró un buen balance entre interpretabilidad y performance.
- El modelo podría mejorarse aplicando **ajuste de hiperparámetros** y explorando algoritmos más complejos.

---

## 🛠 Herramientas utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 🚀 Autoría

Trabajo realizado por **Mariana Renolfi**  
Curso: *Data Science I* - Coderhouse  
Comisión: 75655  
Año: 2025

---
