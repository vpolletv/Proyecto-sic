# Proyecto-sic
https://proyecto-sic-zfjsemh55f2svduasz6gcv.streamlit.app/#simulador-simple-de-caso-para-capacitacion
🎯 Pregunta de Análisis
¿Cuáles son los principales detonantes de frustración en clientes y cómo pueden utilizarse para diseñar escenarios de entrenamiento para agentes de soporte?

💡 Hallazgo Principal
El análisis revela que la demora en los tiempos de respuesta y los fallos técnicos recurrentes son los principales detonantes de frustración en los clientes. A través de la clasificación automatizada, se identificaron patrones claros que permiten priorizar los casos negativos, facilitando el diseño de escenarios de entrenamiento específicos para que los agentes de soporte puedan manejar estas situaciones con mayor empatía y eficacia.

📊 Dataset
El proyecto utiliza datos reales de interacciones de soporte técnico en redes sociales.

Fuente: Dataset Original (TWCS)
Dataset Procesado: Dataset Limpio
Descripción: El dataset procesado incluye análisis de sentimiento y clasificación de detonantes de frustración, optimizado para el entrenamiento de agentes de soporte.
🏗️ Estructura del Proyecto
proyectos/
└── grupo_8/
    ├── data/
    │   ├── dataset_original.csv.txt           # Dataset crudo
    │   └── dataset_limpio.csv.txt             # Dataset procesado
    ├── notebooks/
    │   ├── 01_eda_limpieza_analisis.ipynb     # Eda, limpieza y analisis, proyecto final
    │   ├── V1-proyecto.ipynb                  # Eda, limpieza y analisis, primera parte
    ├── outputs
    ├── app.py                                 # archivo app.py con dashboard en streamlit
    ├── requirements.txt                       # Dependencias del proyecto
  
