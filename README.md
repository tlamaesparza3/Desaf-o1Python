# Desaf-o1Python

# Desafío Alura Store: Análisis de Ventas y Rendimiento

## 📝 Descripción del Proyecto

Este proyecto analiza los datos de ventas de cuatro tiendas de "Alura Store" para determinar cuál de ellas tiene el menor rendimiento. El objetivo final es proporcionar una recomendación basada en datos al propietario, el Señor Juan, sobre qué tienda debería vender para financiar una nueva inversión comercial.

El análisis se centra en cinco aspectos clave del rendimiento de cada tienda:
1.  **Ingresos Totales:** Facturación total generada.
2.  **Categorías Populares:** Los tipos de productos más vendidos.
3.  **Evaluación de Clientes:** El promedio de calificaciones recibidas.
4.  **Productos Más Vendidos:** Identificación de los artículos específicos con mayor rotación.
5.  **Costo de Envío Promedio:** El costo promedio de logística para el cliente.

## 🛠️ Herramientas Utilizadas

* **Lenguaje de Programación:** Python
* **Bibliotecas de Análisis:** Pandas
* **Bibliotecas de Visualización:** Matplotlib, Seaborn
* **Entorno de Desarrollo:** Jupyter Notebook / Google Colab

## 📊 Proceso de Análisis

1.  **Carga de Datos:** Se cargaron los cuatro archivos (`tienda_1 .csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`) en DataFrames de Pandas.
2.  **Cálculo de Métricas:** Para cada tienda, se calcularon las métricas clave (ingresos, promedios de calificación y envío, y productos/categorías más frecuentes).
3.  **Consolidación de Resultados:** Los resultados de las cuatro tiendas se consolidaron en una única tabla comparativa para facilitar la evaluación.
4.  **Visualización:** Se crearon tres gráficos para representar visualmente los hallazgos:
    * Un gráfico de barras para comparar los **Ingresos Totales**.
    * Un gráfico de barras para comparar la **Evaluación Promedio de Clientes**.
    * Un gráfico circular para mostrar la **distribución de las categorías más populares** entre las tiendas.

## 💡 Conclusión y Recomendación

El análisis concluyó que la **Tienda 4** es la que presenta el rendimiento más bajo de manera consistente. Esta conclusión se basa en que dicha tienda tiene:
- Los **ingresos más bajos**.
- La **peor calificación** por parte de los clientes.
- El **costo de envío promedio más alto**.

Por lo tanto, se ha recomendado al Señor Juan que considere la **venta de la Tienda 4**.
