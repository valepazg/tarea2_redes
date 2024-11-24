
# **Tarea 2 - Análisis de Sesgos y Mitigación en Machine Learning**

**Curso:** Algoritmos, Redes y Equidad: Análisis de Sistemas Sociotécnicos  
**Primavera 2024**  
**Departamento:** Ciencias de la Computación, Universidad de Chile  

**Integrantes:**  
- Lucas Carrasco  
- Valeria Gutiérrez  
- Romina Hernández  

---


## **Instrucciones de Ejecución**

El código fuente de esta tarea se encuentra en el archivo `t2.ipynb`, desarrollado en un **Jupyter Notebook**.

1. Se utilizaron las librerías ucimlrepo y AI Fairness 360 de Python, por lo que es necesario ejecutar en un terminal:

```bash
!pip install ucimlrepo
!pip install aif360
!pip install 'aif360[Reductions]'
!pip install 'aif360[inFairness]'
```
2. Abrir el Notebook en un editor de preferencia, asegurando que el contenido de la carpeta `dataset`
está al mismo nivel que el archivo `t2.ipynb`. Ejecutar todas las celdas.

3. Se recomienda abrir el archivo en Google Colab para una mejor y más rápida visualización.
En este caso será necesario importar todos los archivos de la carpeta `dataset` antes de
ejecutar las celdas de importación del dataset.