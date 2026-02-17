# Diplomado en Inteligencia Artificial

**Institución:** Centro de Investigación Científica y de Educación Superior de Ensenada (CICESE) - Universidad Autónoma de Baja California (UABC)

**Instructor:** Dr. Irvin Hussein López Nava

---

## 📚 Módulo 1: Introducción a la Minería de Datos

**Duración total:** 8 horas  
**Modalidad:** Teoría + Prácticas

### 🎯 Objetivo del Módulo

Establecer las bases conceptuales y metodológicas de la minería de datos como componente fundamental de la inteligencia artificial aplicada, con énfasis en aplicaciones en ciencia de materiales y procesos industriales.

---

## 📋 Contenido del Módulo

### 1. Introducción y Fundamentos (1 hora)

**📄 Material teórico:** [`M1-1_Intro.pdf`](M1-1_Intro.pdf)

**Contenido:**
- 1.1 ¿Qué es la minería de datos?
  - Definición y objetivos
  - Ciclo de vida del proceso de minería de datos
- 1.2 Conceptos básicos
  - Atributos y tipos de atributos: nominales, ordinales, discretos, continuos
  - Tareas principales: regresión, clasificación, agrupamiento
  - Clasificación: binaria, multiclase, multi-etiqueta, multi-instancia
- 1.3 Visualización de datos
  - Exploración de datos: histogramas, diagramas de caja, mapas de calor, proyecciones 2D y 3D
  - Herramientas: Pandas, Matplotlib, Seaborn (en Python)

---

### 2. Ejercicios Prácticos e Integración (2 horas)

**📓 Notebook:** [![M1-2_Ejercicios_Visualizacion](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/husseinlopez/diplomadoIA/blob/main/M1-2_Ejercicios_Visualizacion.ipynb)

**Contenido:**
- 2.1 Visualización de conjuntos de datos genéricos
  - Cantidades
  - Distribuciones
  - Proporciones
  - Asociaciones
  - Variables ordenadas
- 2.2 Exploración de un conjunto de datos real
  - Análisis completo del Wine Quality Dataset
  - Identificación de tipos de atributos
  - Detección de problemas en los datos
  - Preparación para modelado

**Ejercicios incluidos:**
- ✅ 3 ejercicios guiados intercalados
- ✅ 1 ejercicio final integrador

---

### 3. Limpieza y Preparación de Datos (1 hora)

**📄 Material teórico:** [`M1-3_Limpieza.pdf`](M1-3_Limpieza.pdf)

**Contenido:**
- 3.1 Calidad de datos y preprocesamiento
- 3.2 Reducción de dimensionalidad
- 3.3 Selección de atributos
- 3.4 Discretización y balanceo de clases

---

### 4. Ejercicios Prácticos e Integración (2 horas)

**📓 Notebook:** [![M1-4_Ejercicios_Limpieza](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/husseinlopez/diplomadoIA/blob/main/M1-6_Ejercicios_Limpieza.ipynb)

**Contenido:**
- 4.1 Limpieza y preprocesamiento
- 4.2 Reducción de dimensionalidad
- 4.3 Selección de atributos
- 4.4 Discretización y balanceo de clases.

---

### 5. Validación y Evaluación de Modelos (1 hora)

**📄 Material teórico:** [`M1-5_Evaluacion.pdf`](M1-5_Evaluacion.pdf)

**Contenido:**
- 5.1 Partición de datos y validación
- 5.2 Métricas de rendimiento

---

### 6. Ejercicios Prácticos e Integración (1 hora)

**📓 Notebook:** [![M1-6_Ejercicios_Validacion](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/husseinlopez/diplomadoIA/blob/main/M1-6_Ejercicios_Validacion.ipynb)

**Contenido:**
- 6.1 Validación de modelo simple
- 6.2 Análisis de resultados
- 6.3 Comparación de métricas
- 6.4 Interpretación de resultados

---

## 🚀 Cómo Usar este Repositorio

### Para Estudiantes

1. **Descargar materiales teóricos:**
   - Haz clic en los archivos PDF y descárgalos
   - Revísalos antes de cada sesión

2. **Trabajar con notebooks:**
   - Haz clic en el badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)
   - El notebook se abrirá en Google Colab
   - **Importante:** Guarda una copia en tu Drive: `File → Save a copy in Drive`
   - Trabaja en tu copia personal

3. **Requisitos previos:**
   - Cuenta de Google (para usar Colab)
   - Conocimientos básicos de Python (variables, funciones, listas)
   - No se requiere instalación local

### Estructura de Archivos

```
diplomado-ia/
├── README.md                               # Este archivo
├── M1-1_Intro.pdf                          # Teoría: Introducción
├── M1-2_Ejercicios_Visualizacion.ipynb     # Práctica: Visualización
├── M1-3_Limpieza.pdf                       # Teoría: Limpieza 
├── M1-4_Ejercicios_Limpieza.ipynb          # Práctica: Limpieza (próximamente)
├── M1-5_Evaluacion.pdf                     # Teoría: Evaluación (próximamente)
└── M1-6_Ejercicios_Validacion.ipynb        # Práctica: Evaluación (próximamente)
```

---

## 💻 Requisitos Técnicos

### Para Notebooks en Google Colab
- ✅ Navegador web moderno (Chrome, Firefox, Safari)
- ✅ Cuenta de Google
- ✅ Conexión a internet estable

### Bibliotecas Utilizadas
Todas se instalan automáticamente en Colab:
- `pandas` - Manipulación de datos
- `numpy` - Operaciones numéricas
- `matplotlib` - Visualización básica
- `seaborn` - Visualización estadística
- `scikit-learn` - Machine learning (en módulos posteriores)

---

## 📖 Bibliografía Principal

1. **Aggarwal, C. C.** (2015). *Data Mining: The Textbook*. Springer.
2. **Wilke, C. O.** (2019). *Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures*. O'Reilly Media.
3. **McKinney, W.** (2017). *Python for Data Analysis*. O'Reilly Media.
4. **Géron, A.** (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. O'Reilly Media.

### Recursos en Línea
- [Documentación de Pandas](https://pandas.pydata.org/docs/)
- [Documentación de Matplotlib](https://matplotlib.org/stable/contents.html)
- [Documentación de Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn Tutorials](https://scikit-learn.org/stable/tutorial/index.html)

---

## 🎓 Relación con el Diplomado

Este módulo forma parte del **tronco común** del diplomado y sienta las bases para:

- **Módulo 2:** Aprendizaje de Máquina
  - Algoritmos supervisados y no supervisados
  - Optimización de hiperparámetros
  - Ensambles y métodos avanzados

- **Módulo 3:** Aprendizaje Profundo
  - Redes neuronales artificiales
  - Redes convolucionales (CNN)
  - Redes recurrentes (RNN)

- **Módulos de Especialización:**
  - Aplicaciones en ciencia de materiales
  - Procesamiento de imágenes científicas
  - Optimización de procesos industriales

---

## 📅 Calendario (Ejemplo)

| Fecha | Sesión | Tema | Material |
|-------|--------|------|----------|
| Martes 10/Feb | 1 | Introducción y Fundamentos | `M1-1_Intro.pdf` |
| Martes 10/Feb | 2 | Ejercicios de Visualización | Notebook Colab |
| Martes 10/Feb | 3 | Limpieza y Preparación | `M1-3_Limpieza.pdf` |
| Martes 17/Feb | 4 | Ejercicios de Limpieza | Notebook Colab |
| Martes 17/Feb | 5 | Evaluación de Modelos | `M1-5_Evaluacion.pdf` |
| Martes 17/Feb | 6 | Ejercicios de Evaluación | Notebook Colab |

---

## ❓ Preguntas Frecuentes

### ¿Necesito instalar Python en mi computadora?
No. Todos los ejercicios se realizan en Google Colab, que funciona completamente en la nube.

### ¿Qué pasa si no tengo experiencia en programación?
Los notebooks están diseñados para diferentes niveles. Incluyen explicaciones detalladas y ejemplos paso a paso. Se recomienda revisar los fundamentos de Python antes de comenzar.

### ¿Puedo modificar los notebooks?
Sí, pero asegúrate de guardar tu propia copia primero (`File → Save a copy in Drive`). Los cambios en la versión compartida no se guardarán.

### ¿Los notebooks funcionan sin conexión?
No. Google Colab requiere conexión a internet. Para trabajar offline, considera instalar Jupyter Notebook localmente.

---

## 📬 Contacto

**Instructor:** Dr. Irvin Hussein López Nava

**Institución:**
- Centro de Investigación Científica y de Educación Superior de Ensenada (CICESE)
- Facultad de Ciencias, Universidad Autónoma de Baja California (UABC)

---

## 📄 Licencia

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

Este material educativo está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Licencia Creative Commons Atribución 4.0 Internacional (CC BY 4.0)</a>.

**Esto significa que puedes:**
- ✅ **Compartir** — copiar y redistribuir el material en cualquier medio o formato
- ✅ **Adaptar** — remezclar, transformar y construir a partir del material para cualquier propósito, incluso comercialmente

**Bajo los siguientes términos:**
- 📌 **Atribución** — Debes dar crédito de manera adecuada, brindar un enlace a la licencia, e indicar si se han realizado cambios. Puedes hacerlo en cualquier forma razonable, pero no de forma tal que sugiera que tienes el apoyo del licenciante o lo recibes por el uso que haces.

### Cómo citar este material:

**Formato APA:**
```
López Nava, I. H. (2025). Diplomado en Inteligencia Artificial - Módulo 1: 
Introducción a la Minería de Datos. CICESE-UABC. 
https://github.com/husseinlopez/diplomadoIA
Licencia: CC BY 4.0
```

**Formato breve:**
```
Material basado en "Diplomado en IA - Módulo 1" por Dr. Irvin Hussein López Nava 
(CICESE-UABC). Disponible en: https://github.com/husseinlopez/diplomadoIA
Licencia: CC BY 4.0
```

Para más información sobre esta licencia, visita: https://creativecommons.org/licenses/by/4.0/deed.es

---

## ⭐ Actualizaciones

- **23/ene/2026** - Módulo 1 primera parte (Introducción [1 hr]; Ejercicios de Visualización [2 hrs])
- **30/ene/2026** - Módulo 1 primera parte (Limpieza y Preparación de Datos [1 hr])
- **15/feb/2026** - Módulo 1 segunda parte (Ejercicios Prácticos e Integración [2 hrs]; Validación y Evaluación de Modelos [1 hr]; Ejercicios Prácticos e Integración [1 hr])

---

**¡Bienvenidos al mundo de la Minería de Datos y la Inteligencia Artificial! 🚀**
