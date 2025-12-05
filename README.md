# Alura-Store-Challange
El presente repositorio aloja el Notebook **Challange_Alura_Store.ipynb** donde se realizó un análisis de ventas de cuatro tiendas de la cadena Alura Store en Latinoamérica, a partir de datos abiertos en CSV. El objetivo principal es el uso de la librería pandas en un entorno cercano al real para la toma de decisiones.

## Contenido
1. [Descripción del proyecto](#descripción-del-proyecto)
2. [Elementos del Notebook](#elementos-del-notebook)
3. [Requisitos](#requisitos)
4. [Licencia](#licencia)
5. [Autor](#autor)

## Descripción del proyecto
Con el análisis exploratorio de datos se busca contestar las siguientes preguntas objetivo:

* ¿Cuál es la facturación total de cada tienda?
* ¿Qué categorías de productos generan más ingresos?
* ¿Cuál es la calificación promedio otorgada por los clientes?
* ¿Qué productos son los más y menos vendidos?
* ¿Cuál es el costo de envío promedio por tienda?

## Elementos del Notebook
El archivo fue dividido en secciones para su lectura:

| Sección |Contenido |                                                               
| - | - |
| 1. Importación de datos|Se integran 4 archivos con información de ventas y el inventario individual.|
| 2. Análisis de facturación |Se hace la suma de las ventas por tienda, se normaliza el resultado.|
| 3. Ventas por categoría |Se agrupan (`.groupby`) los productos por categorías para conocer los valores de compras.|
| 4. Calificación promedio |Promedio de la satisfacción del cliente por tienda.|
| 5. Productos más o menos vendidos |Top 5 de los productos que más y menos se venden. |
| 6. Envío promedio por tienda |Costo del envío para transporte de productos. |
| 7. Visualización de datos |Gráficos generados con `matplotlib` para la Visualizaciónde la información.|
| 8. Informe Final |Reporte acerca de los datos generados, incluyendo gráficos y la síntesis del análisis.|       

## Requisitos
* Python (v. 3.8 en adelante)
* Librerías de pandas y matplotlib
* Google colab o jupyterlab

## Licencia
Este repositorio es distribuido najo la licencia MIT. Consulte el archivo **LICENSE** para más detalles.

## Autor 
Juan Alberto Andrade Nieto
Geógrafo, interesado en la tecnología y la ciencia de datos.
[LinkedIn](https://www.linkedin.com/in/juan-andrade-geo/)
