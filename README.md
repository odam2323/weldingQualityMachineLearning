# Identificación de Muestras de Soldadura mediante Machine Learning

Este repositorio contiene un proyecto desarrollado para el curso de Introducción al Machine Learning, enfocado en el aprendizaje supervisado para la identificación y clasificación de muestras de soldadura. 

## 📖 Marco del Proyecto

El objetivo principal de este proyecto es hacer uso de técnicas de Machine Learning para etiquetar correctamente imágenes de soldaduras, clasificándolas como buenas o malas. Esta clasificación automatizada tiene el propósito de permitir una evaluación objetiva del desempeño de determinados trabajadores.

## 🏢 Trasfondo del Negocio

El desarrollo se enmarca en la necesidad práctica que tienen las empresas para la selección y evaluación de sus soldadores. Se concentra particularmente en el trabajo operativo dentro de los talleres de soldadura, buscando mejorar la calidad del personal disponible en cualquier taller.

## 🎯 Alcance y Metodología

Para diferenciar a un buen soldador de uno con áreas de mejora, el sistema evalúa la calidad de la soldadura basándose en un conjunto de imágenes recopiladas en un taller de la Universidad Nacional. 

* Se lleva a cabo un entrenamiento supervisado utilizando imágenes de prueba previamente caracterizadas con sus respectivas etiquetas de calidad.
* El objetivo final es que cualquier cliente pueda ingresar imágenes futuras en el modelo para interpretar y calificar el desempeño de sus empleados o postulantes.

## 🚀 Resultados Técnicos

* Para la identificación de etiquetas en este caso de aprendizaje supervisado, el modelo de máquina de vectores de soporte (Support Vector Machine) logró los mejores resultados.
* Se determinó que este algoritmo presenta un menor costo computacional adecuado para la cantidad y el tipo de imágenes utilizadas en este estudio.

## 🛠️ Tecnologías y Herramientas Utilizadas

* **Lenguaje de Programación:** Python 3.
* **Entorno de Desarrollo:** Jupyter Notebook.
* **Enfoque de Modelado:** Machine Learning orientado al Aprendizaje Supervisado.
* **Algoritmo Principal:** Máquina de Vectores de Soporte (Support Vector Machine - SVM). Se determinó que este algoritmo de clasificación logró los mejores resultados en la identificación de las etiquetas, requiriendo un menor costo computacional para la cantidad y tipo de imágenes procesadas en el estudio.
* **Tipo de Datos:** Procesamiento, lectura y clasificación de imágenes representativas de las muestras de soldadura.

## 👥 Equipo de Trabajo e Institución

**Integrantes:**
* Sarah Fonseca
* Christian Camilo Barriga
* Andrés Serrano

Este proyecto se desarrolló en la **Facultad de Ingeniería de la Universidad Nacional de Colombia**, contando con:
* **Profesor:** Fabio Augusto Gonzalez
* **Asistente docente y diseño de imágenes:** Rosa Alejandra Superlano Esquibel
* **Coordinador de virtualización:** Edder Hernández Forero
