# SIGMED_LEARNING
Somos un grupo de estudiantes de la UAO, que por medio de la clase de integración de señales adquirimos conocimientos sobre conceptos clave de procesamiento de señales, como el demostrado, el filtrado, la transformada de Fourier, la detección de eventos y la extracción de características utilizando las capacidades de programación de Python

Extraccion CARACTERÍSTICAS ECG
Se realizó utilizando bibliotecas especializadas en procesamiento de señales, como NumPy, SciPy y biosppy. Estas bibliotecas tienen funciones y algoritmos eficientes para manipular y analizar las señales de ECG, para facilitar la implementación de los métodos de extracción de características.

Analisis Exploratorio de Datos
Mediante el proceso de examinar y comprender los datos relacionados con la asistencia de los pacientes a las citas de resonancia magnética y desarrollar un modelo que pueda predecir la probabilidad de que un paciente falte a una cita.Por lo que utilizamos una base de datos donde se han recopilado los datos relacionados con las citas de resonancia magnética, incluyendo características como la fecha y hora de la cita, el número del paciente,ID, el motivo de la cita, etc. Luego, se realiza un análisis exploratorio de los datos para comprender su distribución, identificar posibles valores atípicos o datos faltantes, y descubrir patrones o relaciones entre las variables. Esto implica el uso de bibliotecas como Pandas, NumPy y Matplotlib para realizar visualizaciones, cálculos estadísticos y manejo de datos. Siguiendo con el preprocesamiento de los datos para prepararlos para su uso en el modelo de predicción. Esto puede incluir la limpieza de datos faltantes, la codificación de variables categóricas, la normalización de variables numéricas, etc. Luego se realiza la ingeniería de datos donde realizamos el escalamiento de los datos, cálculos de la edad teniendo en cuenta la fecha de nacimiento y la fecha de creación de la cita, los cálculos de citas por cada paciente, en donde se observa cuantas citas se le han asignado, a cuántos ha asistido y cuántos ha cancelado, también se realiza el cálculo de citas por horario en donde muestra las horas más acertadas de que un paciente asista y en cuáles es más probable que falle; el calculo de citas por dia de la semana, donde tambien se puede observar que dia de la semana es mas probable que el paciente asista y que dia es mas probable que falte, etc. uso de LogisticRegression. cálculos de la edad teniendo en cuenta la fecha de nacimiento y la fecha de creación de la cita, los cálculos de citas por cada paciente, en donde se observa cuántas citas se le han asignado, a cuántos ha asistido y horas ha cancelado, también se realice el calculo de citas por horario en donde muestra las horas mas acertadas de que un paciente asista y en cuales es mas probable que falle; el calculo de citas por dia de la semana, donde tambien se puede observar que dia de la semana es mas probable que el paciente asista y que dia es mas probable que falte, etc. uso de LogisticRegression. cálculos de la edad teniendo en cuenta la fecha de nacimiento y la fecha de creación de la cita, los cálculos de citas por cada paciente, en donde se observa cuántas citas se le han asignado, a cuántos ha asistido y horas ha cancelado, también se realice el calculo de citas por horario en donde muestra las horas mas acertadas de que un paciente asista y en cuales es mas probable que falle; el calculo de citas por dia de la semana, donde tambien se puede observar que dia de la semana es mas probable que el paciente asista y que dia es mas probable que falte, etc. uso de LogisticRegression. a cuantos ha asistido y cuantos ha cancelado, también se realiza el cálculo de citas por horario en donde muestra las horas más acertadas de que un paciente asista y en cuales es más probable que falle; el calculo de citas por dia de la semana, donde tambien se puede observar que dia de la semana es mas probable que el paciente asista y que dia es mas probable que falte, etc. uso de LogisticRegression. a cuantos ha asistido y cuantos ha cancelado, también se realiza el cálculo de citas por horario en donde muestra las horas más acertadas de que un paciente asista y en cuales es más probable que falle; el calculo de citas por dia de la semana, donde tambien se puede observar que dia de la semana es mas probable que el paciente asista y que dia es mas probable que falte, etc. uso de LogisticRegression.

Datos fisicos y Antroprometicos
Utilizamos una base de datos en donde nos suministran datos físicos y datos antropométricos de un grupo de tenistas, luego se realiza un filtrado de los datos, en donde se eliminan los tenistas que no tenían datos completos, para reducir la dimensionalidad del dataframe se realiza un análisis de PCA Y KPCA, con el análisis PCA buscamos poder manejar las dimensiones cortas, es decir que contengan la mayor varianza en la reducción de dimensiones, a partir de esa reducción se usó un clasificador KNN para determinar de acuerdo a los datos físicos y datos antropométricos si un paciente era de categoría 0 (rendimiento bajo) o 1 (rendimiento medio), con el análisis KPCA utilizamos una métrica no lineal, con el fin de variar el Kernel de entrada y poder observar la distribución de los datos, analizando esta lineal de datos se pudo determinar que kernel se podría usar en el clasificador.
