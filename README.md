# Prediccion para la aprobación de prestamos bancarios

El objetivo principal de este proyecto es desarrollar un modelo de machine learning capaz de predecir la probabilidad de aprobación de un préstamo bancario basándose en diversas características del solicitante. Esto permite a las instituciones financieras automatizar y optimizar el proceso de evaluación de riesgos, mejorando la eficiencia y reduciendo posibles pérdidas.
Se utilizó Pandas para limpiar y transformar los datos, manejando valores faltantes, eliminando datos atípicos y codificando variables categóricas.

# Instrucciones de instalacion
Para ejecutar este proyecto, necesitarás tener Python 3.x instalado en tu sistema, junto con las siguientes bibliotecas:
- Pandas
- Numpy
- Scikit-learn
Puedes instalar estas bibliotecas utilizando pip:
pip install pandas scikit-learn numpy

# Flujo de codigo
- Primero se cargan los conjuntos de datos desde un archivo CSV, convirtiendolos en un dataframe
- Se juntan ambos dataframes en uno solo, facilitando el proceso de limpieza de datos
- Las variables categoricas se pasan a valores booleanos mediante el argumento get_dummies()
- Se hace una revision de valores faltantes, en caso de haber, se hace una imputación con el valor mas frecuente dentro de la columna
- Se carga el dataframe limpio a CSV para poder exportar y empezar el proceso de machine learning
