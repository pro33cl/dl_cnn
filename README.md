🧠 Clasificación de Imágenes con Redes Neuronales Convolucionales (CNN)

Notebook: dl_cnn.ipynb

📄 Descripción General

Este notebook implementa un flujo completo de Deep Learning para clasificación de imágenes, utilizando redes Fully Connected y Redes Neuronales Convolucionales (CNN). Incluye carga de datos, preprocesamiento, entrenamiento, evaluación con métricas y visualización de curvas de desempeño.

📂 Contenidos del Notebook
1️⃣ Carga y preparación de datos

- Importación de los conjuntos cnn_train_X.npy, cnn_train_y.npy, cnn_test_X.npy, cnn_test_y.npy.
- Revisión de dimensiones, formatos y estructura.
- Codificación de etiquetas con OneHotEncoder.

2️⃣ Modelo Fully Connected

- Construcción de una red neuronal multicapa (Dense).
- Entrenamiento sobre imágenes preprocesadas.
- Evaluación con accuracy, pérdida y matriz de confusión.

3️⃣ Modelo CNN

- Implementación de una red convolucional básica.
- Capas Conv2D, MaxPooling, Flatten y Dense.
- Monitoreo de accuracy y loss por época.

4️⃣ Modelo CNN Avanzado

- Arquitectura más profunda/robusta.
- Mejoras en capas, filtros y regularización.
- Evaluación comparativa entre modelos.
- Graficación de curvas de entrenamiento.

5️⃣ Predicciones finales

- Uso del modelo entrenado para clasificar imágenes sin etiquetas.
- Visualización de las imágenes junto a su etiqueta predicha.

🛠️ Tecnologías Utilizadas

- Python 3
- NumPy, Pandas
- TensorFlow / Keras
- Matplotlib

scikit-learn (OneHotEncoder)

▶️ Cómo Ejecutar el Notebook

1. Clonar el repo:
git clone <URL-de-tu-repositorio>
cd <carpeta>

2. (Opcional) Crear entorno virtual:
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3. Instalar dependencias:
pip install -r requirements.txt


4. Ejecutar:
jupyter notebook dl_cnn.ipynb

🎯 Objetivo del Proyecto

Este notebook tiene como finalidad introducir y practicar conceptos esenciales en la clasificación de imágenes con Deep Learning, comparando arquitecturas Fully Connected con CNN y analizando su rendimiento.

📬 Contacto

Proyecto desarrollado por Héctor Rubilar Valenzuela.
