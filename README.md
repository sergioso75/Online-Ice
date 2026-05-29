# Online 
# README - Proyecto de Análisis de Videojuegos Ice Online Shop

## Descripción del proyecto

Este proyecto se enfoca en el análisis de datos de la tienda en línea **Ice**, una plataforma dedicada a la venta de videojuegos a nivel mundial. El objetivo principal fue identificar patrones que permitan detectar qué factores hacen que un videojuego tenga éxito comercial, utilizando información histórica sobre ventas, plataformas, géneros, reseñas de usuarios y críticos, clasificaciones ESRB y regiones de venta.

El análisis busca ayudar a la empresa a:

* Comprender el comportamiento del mercado de videojuegos.
* Detectar plataformas y géneros con mayor potencial.
* Identificar tendencias de consumo por región.
* Evaluar el impacto de las reseñas en las ventas.
* Generar recomendaciones para campañas y estrategias futuras.

---

# Problema que resuelve el proyecto

La industria de los videojuegos cambia constantemente debido a la aparición de nuevas plataformas, cambios en las preferencias de los usuarios y tendencias regionales.

El principal problema que se buscó resolver fue:

> **¿Cómo identificar los videojuegos y plataformas con mayor probabilidad de éxito comercial utilizando datos históricos de ventas y comportamiento de usuarios?**

La empresa necesitaba comprender:

* Qué plataformas generan mayores ventas.
* Qué géneros son más rentables.
* Cómo influyen las calificaciones de usuarios y críticos.
* Qué diferencias existen entre mercados como Norteamérica, Europa y Japón.
* Qué tendencias pueden servir para planificar campañas futuras.

Gracias al análisis exploratorio y estadístico realizado, se logró obtener información valiosa para apoyar la toma de decisiones comerciales.

---

# Metodología utilizada

## 1. Carga y exploración inicial de datos

Se cargó el conjunto de datos con información histórica de videojuegos y se realizó una exploración inicial para identificar:

* Tipos de datos.
* Valores ausentes.
* Columnas relevantes.
* Posibles inconsistencias.

También se revisó la estructura general del dataset para comprender las variables disponibles.

---

## 2. Limpieza y preparación de datos

Durante esta etapa se realizaron diferentes procesos de limpieza:

### Cambios aplicados

* Conversión de nombres de columnas a minúsculas.
* Corrección de tipos de datos.
* Conversión de columnas numéricas.
* Tratamiento de valores ausentes.
* Eliminación de datos inconsistentes.

### Variables modificadas

Se ajustaron principalmente las columnas:

* `year_of_release`
* `critic_score`
* `user_score`
* `rating`

Esto permitió trabajar correctamente con análisis estadísticos y visualizaciones.

---

## 3. Creación de nuevas variables

Se creó una nueva columna de:

* **Ventas totales**, calculadas a partir de las ventas regionales.

Esta variable permitió evaluar el rendimiento global de cada videojuego.

---

## 4. Análisis exploratorio de datos (EDA)

Se desarrolló un análisis exploratorio para identificar patrones importantes.

### Actividades realizadas

* Análisis de videojuegos lanzados por año.
* Identificación de plataformas con mayores ventas.
* Detección de plataformas en crecimiento y en declive.
* Comparación de ventas entre plataformas.
* Evaluación de géneros más rentables.
* Visualización mediante gráficas de barras, líneas y dispersión.

También se estudió el comportamiento de las plataformas a lo largo del tiempo para determinar cuáles seguían siendo relevantes para años futuros.

---

## 5. Análisis de reseñas y correlaciones

Se evaluó cómo influyen las reseñas de usuarios y críticos en las ventas de videojuegos.

### Técnicas utilizadas

* Diagramas de dispersión.
* Cálculo de correlaciones.
* Comparación entre plataformas.

El análisis se enfocó especialmente en la plataforma PS4 y posteriormente se comparó con otras plataformas.

---

## 6. Análisis regional

Se construyó un perfil de usuario para tres regiones:

* Norteamérica (NA)
* Europa (UE)
* Japón (JP)

En cada región se analizaron:

* Plataformas más populares.
* Géneros con mayores ventas.
* Clasificaciones ESRB predominantes.

Esto permitió identificar diferencias importantes entre mercados.

---

## 7. Pruebas de hipótesis

Se realizaron pruebas estadísticas para validar hipótesis relacionadas con:

* Diferencias entre calificaciones de usuarios en Xbox y PC.
* Diferencias entre géneros de videojuegos.

Para ello se utilizaron:

* Filtrado de datos.
* Eliminación de valores nulos.
* Comparación de medias.
* Pruebas estadísticas.

---

# Principales conclusiones

## 1. Las plataformas cambian constantemente

El análisis mostró que muchas plataformas que fueron populares en el pasado dejaron de generar ventas con el tiempo.

Plataformas como:

* PS
* PS2
* GBA
* DS

perdieron relevancia frente a plataformas más recientes.

Mientras que:

* PS4
* PS3
* X360
* Wii
* 3DS

mantuvieron mejores resultados en ventas.

---

## 2. Los géneros más rentables

Los géneros con mejores ventas fueron:

* Action
* Shooter
* Sports
* Fighting
* Platform

Estos géneros demostraron ser los más atractivos para el mercado.

---

## 3. Las reseñas sí influyen en las ventas

Se encontró una relación entre las calificaciones de críticos y usuarios con el desempeño comercial de algunos videojuegos.

Las reseñas positivas tienden a relacionarse con mayores ventas, especialmente en plataformas populares.

---

## 4. Existen diferencias importantes entre regiones

Norteamérica y Europa presentan comportamientos similares en plataformas y géneros.

Sin embargo, Japón mostró diferencias más marcadas en preferencias de consumo.

Esto demuestra la importancia de adaptar estrategias de marketing según la región.

---

## 5. Los datos históricos ayudan a predecir tendencias

El análisis de plataformas activas y ventas recientes permitió identificar tendencias útiles para construir estrategias futuras y estimar el comportamiento del mercado para años posteriores.

---

# Herramientas utilizadas

Durante el proyecto se utilizaron principalmente:

* Python
* Pandas
* NumPy
* Matplotlib
* Análisis estadístico
* Visualización de datos

---

# Resultados esperados del proyecto

Gracias a este análisis, la empresa puede:

* Mejorar la toma de decisiones.
* Identificar videojuegos con mayor potencial.
* Planificar campañas publicitarias más efectivas.
* Enfocar inversiones en plataformas y géneros rentables.
* Comprender diferencias entre mercados internacionales.

---

# Conclusión general

Este proyecto permitió transformar datos históricos de videojuegos en información útil para la toma de decisiones estratégicas.

A través de técnicas de limpieza, análisis exploratorio y pruebas estadísticas, se logró identificar patrones importantes relacionados con plataformas, géneros, ventas y comportamiento regional.

Los resultados demuestran que el análisis de datos es una herramienta fundamental para comprender tendencias del mercado y apoyar estrategias comerciales dentro de la industria de los videojuegos.
