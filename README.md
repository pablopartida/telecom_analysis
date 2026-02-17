📊 Análisis de Clientes – ConnectaTel
📌 Descripción del Proyecto

Este proyecto analiza el comportamiento de uso de clientes de una empresa de telecomunicaciones (ConnectaTel) con el objetivo de comprender patrones de consumo, detectar comportamientos atípicos y segmentar usuarios según su nivel de actividad.

El análisis busca generar insights accionables que permitan optimizar la oferta comercial y mejorar la experiencia del cliente.

🎯 Objetivos del Negocio

Identificar segmentos de clientes según uso de llamadas y mensajes.

Detectar valores atípicos que puedan indicar comportamientos inusuales o errores.

Analizar cómo varía el uso según edad y tipo de plan.

Extraer patrones que ayuden a diseñar mejores planes comerciales.

Apoyar decisiones estratégicas basadas en datos.

📂 Datasets Utilizados

Se trabajó con tres fuentes principales:

plans.csv
Información de los planes disponibles (precio, minutos incluidos, GB incluidos, costos adicionales).

users_latam.csv
Información de clientes: edad, ciudad, fecha de registro y plan contratado.

usage.csv
Detalle del uso real de servicios:

Llamadas (duración)

Mensajes (longitud)

🧪 Etapas del Análisis
1️⃣ Carga y Exploración Inicial

Importación de los datasets.

Revisión de estructura, tipos de datos y primeras observaciones.

2️⃣ Evaluación de Calidad de Datos

Identificación de valores nulos.

Detección de sentinels.

Revisión de fechas fuera de rango.

Análisis de missing estructural vs missing real.

3️⃣ Limpieza y Transformación

Reemplazo de sentinels.

Conversión de fechas a formato datetime.

Creación de variables auxiliares.

Agregación de métricas por usuario.

4️⃣ Análisis Descriptivo

Estadísticas resumidas.

Distribuciones mediante histogramas.

Identificación de outliers con método IQR.

5️⃣ Visualización

Histogramas segmentados por plan.

Boxplots para evaluar dispersión y asimetría.

Countplots para segmentación categórica.

6️⃣ Segmentación

Creación de grupos de uso (Bajo, Medio, Alto).

Segmentación por edad (rangos fijos).

Análisis comparativo entre segmentos.

7️⃣ Insights Ejecutivos

Identificación del segmento dominante (Uso medio).

Detección de heavy users y oportunidades y necesidades mercadológicas.


🚀 Cómo Ejecutar el Proyecto

https://colab.research.google.com/drive/1o-iusL_nD-QGGbdPlKjhl-p2lJhCVsDS?usp=sharing
