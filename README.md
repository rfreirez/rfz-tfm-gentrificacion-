# Trabajo Final de Maestría

## Tema

Identificación de factores característicos del proceso de gentrificación y su detección en barrios de Madrid.

## Ficheros

* **anexos:** se listan las diferentes imágenes correspondiente a los gráficos de barras para el análisis de evolución de los diferentes indicadores para cada barrio de Madrid en los años 2016, 2018, 2019.

* **original_data:*** Directorio donde se encuentra almacenado todos los archivos que han sido descargados desde las fuentes de datos.

* **data_preprocesada_N1:** Directorio donde se encuentra almacenado todos los archivos separados por año para cada indicador.

* **data_preprocesada_N2:** Directorio donde se encuentra almacenado todos los archivos para cada indicador unificado los años.

* **data_preprocesada_N3:** Directorio donde se almacenan los archivos de datos, resultado del proceso de limpieza/

* **dataset:** Directorio donde se almacena los archivos correspondientes al conjunto de datos final usado para la generación de modelo y el conjunto de datos etiquetado después del proceso de clusterización.

* **src/etl_python/etl_extract_data.ipynb:** Notebook Python, que permite la lectura de las diferentes fuentes de datos e integración con los datos geográficos de los barrios.

* **src/analisis_python/limpieza_datos.ipynb:** Notebook Python, que permite la limpieza de los conjuntos de datos generados.

* **src/analisis_python/analisis_datos_individual.ipynb:** Notebook Python, que permite realizar un análisis visual y estadístico.

* **src/analisis_python/analisis_datos_integrado.ipynb:** Notebook Python, que permite generar el modelo de agrupamiento mediante el algoritmo K-means, de aprendizaje no supervisado.