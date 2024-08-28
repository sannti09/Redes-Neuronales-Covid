#Santiago Rueda


# Paso 1: Recopilación de Datos

## Conjunto de Datos:
- Utiliza un conjunto de imágenes de radiografías de tórax etiquetadas como “COVID-19” y “No COVID-19”.
- Puedes encontrar conjuntos de datos públicos disponibles en línea, como el COVID-19 Radiography Database en Kaggle.

# Paso 2: Preprocesamiento de Datos

## Balanceo de Clases:
- Dado que los casos de COVID-19 son menos frecuentes, aplicaremos undersampling para equilibrar las clases.
- Selecciona una cantidad igual de imágenes de ambas clases (COVID-19 y No COVID-19) al azar.

# Paso 3: Creación del Modelo

## Arquitectura de Red Neuronal:
- Utiliza una red neuronal convolucional (CNN) para extraer características de las imágenes.
- Puedes diseñar tu propia arquitectura o utilizar una preentrenada, como VGG16, ResNet, o Inception.

## Entrenamiento del Modelo:
- Divide tus datos en conjuntos de entrenamiento, validación y prueba.
- Entrena el modelo utilizando las imágenes de entrenamiento.
- Ajusta los hiperparámetros (número de capas, tamaño del lote, tasa de aprendizaje, etc.).

# Paso 4: Evaluación del Modelo

## Métricas de Evaluación:
- Calcula métricas como precisión, recall, F1-score y exactitud.
- Realiza una matriz de confusión para evaluar el rendimiento del modelo.

# Paso 5: Validación y Ajustes

## Validación Cruzada:
- Utiliza validación cruzada para evaluar la robustez del modelo.
- Ajusta los hiperparámetros según los resultados de la validación cruzada.

# Paso 6: Inferencia

## Predicciones:
- Utiliza el modelo entrenado para predecir si una nueva radiografía de tórax pertenece a la clase “COVID-19” o “No COVID-19”.

# Conclusiones
- Documenta tus resultados, aprendizajes y posibles mejoras.
- Comparte tus hallazgos con la comunidad científica y médica.
