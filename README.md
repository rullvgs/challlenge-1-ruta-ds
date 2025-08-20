# 📊 Análisis de Rendimiento de Tiendas "Alura Store"

## 📝 Descripción

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre las ventas y el rendimiento de cuatro sucursales de la cadena de tiendas "Alura Store". El objetivo principal es identificar la tienda con el rendimiento más bajo para proporcionar una recomendación basada en datos al propietario, el Sr. Juan, sobre qué sucursal vender para financiar un nuevo emprendimiento.

## 🎯 Objetivo del Análisis

El objetivo es claro: **identificar la tienda menos eficiente de la cadena Alura Store**. Para lograrlo, se analizaron los siguientes factores clave:

-   Ingresos totales por tienda.
-   Calificaciones promedio de los clientes.
-   Costos de envío promedio.
-   Categorías y productos más vendidos en cada sucursal.

## 🗃️ Conjunto de Datos

El análisis se realizó utilizando cuatro archivos de datos en formato `.csv`, cada uno correspondiente a una tienda:

-   `tienda_1.csv`
-   `tienda_2.csv`
-   `tienda_3.csv`
-   `tienda_4.csv`

Cada registro en los archivos contiene información detallada sobre cada transacción, incluyendo producto, categoría, precio, costo de envío, fecha, vendedor y calificación del cliente.

## 🛠️ Herramientas Utilizadas

-   **Lenguaje:** Python 3
-   **Bibliotecas de Análisis:** Pandas
-   **Bibliotecas de Visualización:** Matplotlib y Seaborn
-   **Entorno:** Jupyter Notebook (`.ipynb`)

## 📈 Metodología

El proyecto se estructuró siguiendo los siguientes pasos:

1.  **Carga y Limpieza de Datos:** Se cargaron los cuatro archivos CSV y se consolidaron en un único DataFrame de Pandas. Se realizaron tareas de limpieza básicas.
2.  **Análisis Exploratorio de Datos (EDA):** Se calcularon métricas agregadas para comparar el rendimiento de las tiendas, incluyendo la suma de ingresos, el promedio de calificaciones y el promedio de costos de envío.
3.  **Análisis Comparativo Detallado:** Se desglosaron las ventas por categorías y productos para cada tienda, permitiendo una comparación directa de sus fortalezas y debilidades.
4.  **Visualización de Datos:** Se generaron gráficos de barras y diagramas comparativos para ilustrar los hallazgos de manera clara y efectiva.
5.  **Síntesis y Conclusión:** Se interpretaron los resultados y se redactó un informe final con una recomendación justificada.

## 💡 Conclusión Principal

El análisis concluyó que la **Tienda 4** es la candidata ideal para la venta. A pesar de tener costos de envío competitivos, su **bajo rendimiento en ingresos totales** es el factor decisivo. A diferencia de otras tiendas con problemas operativos solucionables (como la Tienda 1 y sus bajas calificaciones), el problema de la Tienda 4 es estructural y de fondo, convirtiéndola en el activo menos productivo.
