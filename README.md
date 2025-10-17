# Data-Scientist-Technical-Challenge

Este proyecto tiene como objetivo principal desarrollar un modelo de clasificación que permita maximizar las ganancias económicas de la empresa a través de la detección eficiente de eventos relevantes (por ejemplo, fraudes).

A lo largo del análisis se aplican diferentes técnicas de preprocesamiento, balanceo de clases, selección de variables y ajuste de hiperparámetros, evaluando múltiples algoritmos de machine learning. Además, se realiza una optimización del umbral de decisión, no solo para mejorar las métricas clásicas (como precisión, recall y F1-score), sino especialmente para optimizar el impacto económico real, considerando los costos y beneficios asociados a cada tipo de predicción.

El modelo final es seleccionado en función de su capacidad para:

Detectar la mayor cantidad de eventos relevantes (recall),

Mantener un equilibrio entre sensibilidad y precisión (F1-score),

Y sobre todo, maximizar la ganancia neta estimada para la empresa.

# Archivos del Repositorio

Readme.md : Introducción del proyecto

Challenger.ipynb : Código fuente utilizado

MercadoLibre Inc. Data Scientist Hiring Test - Fraud Dataset  - Data.csv : Base original

# Modelos Entrenados

1. Regresión Logística (Logistic Regression)

2. SVM (Support Vector Machine)

3. Random Forest

4. XGBoost (Extreme Gradient Boosting)


# Modelo Seleccionado

Se guardo el modelo seleccionado en .pkl por si se requiere para hacer diferentes validaciones
