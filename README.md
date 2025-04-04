# 🏋️‍♂️ Predicción de Cancelación de Clientes – Model Fitness

## Descripción general
Este proyecto analiza el comportamiento de los clientes de un gimnasio ficticio, Model Fitness, con el objetivo de predecir la probabilidad de cancelación y segmentar usuarios mediante técnicas de machine learning. Se busca proponer estrategias para mejorar la retención de clientes.

## Objetivos
- Predecir la probabilidad de cancelación (churn) de los clientes usando modelos de clasificación
- Identificar patrones de comportamiento en los usuarios
- Segmentar clientes en clústeres mediante K-means
- Formular recomendaciones para reducir la rotación de clientes

## Herramientas utilizadas
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Modelos: Regresión Logística y Random Forest
- Clustering: K-means, linkage, dendrogramas
- Jupyter Notebook

## Principales hallazgos
- El modelo de Random Forest obtuvo mejores métricas que la regresión logística
- Se identificaron 5 clústeres de usuarios con diferentes tasas de cancelación
- Los clientes con mayor antigüedad y contratos largos mostraron menor probabilidad de irse
- Se recomendó enfocar esfuerzos en usuarios nuevos con baja frecuencia de asistencia

## Dataset
`gym_churn_us.csv`: datos simulados de clientes del gimnasio, incluyendo características personales, comportamiento de uso y datos contractuales.
