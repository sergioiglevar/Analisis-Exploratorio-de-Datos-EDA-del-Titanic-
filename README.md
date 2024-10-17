# 📊 Análisis Exploratorio de Datos (EDA) del Titanic


![Portada](https://github.com/sergioiglevar/nevo-Titanic/blob/main/Pictures/portada.jfif)

## 🚢 Introducción
En este proyecto, hemos realizado un análisis exhaustivo de los datos del Titanic para identificar los factores que influenciaron la supervivencia de los pasajeros. Utilizamos técnicas avanzadas de análisis de datos y visualización para desentrañar patrones y tendencias.

## 🔄 Procesamiento de Datos

### 🧹 Limpieza de Datos
Para abordar los valores nulos en la columna `Age`, aplicamos la media de 29.70 años. Utilizamos `sns.histplot` para visualizar la distribución de las edades tras la imputación. Sin embargo, observamos una sobresaturación en la media de la edad, lo que no representa adecuadamente la variabilidad de los datos.

### ⚙️ Propuesta de Mejora
Para obtener estimaciones de edad más precisas, propusimos implementar un modelo K-Nearest Neighbors (KNN). Este modelo utiliza las características del conjunto de datos para predecir las edades faltantes de manera más realista.

1. **Desarrollo del Modelo KNN:** Entrenar y validar el modelo utilizando datos completos.
2. **Evaluación de Resultados:** Comparar la precisión del modelo KNN frente al método de imputación por media.
3. **Implementación:** Aplicar el modelo KNN al conjunto de datos y analizar los resultados.

---

## 📈 Análisis Exploratorio de Datos (EDA)

### 📊 Distribución de Supervivientes y No Supervivientes
- **Total de pasajeros:** 891
- **Supervivientes:** 342 (38.4%)
- **No supervivientes:** 549 (61.6%)

*Visualización: Gráfica de barras mostrando el número de supervivientes y no supervivientes.*

### 👩‍🦰 Supervivencia por Género
- **Mujeres:** 74.2% de supervivencia.
- **Hombres:** 18.9% de supervivencia.

*Visualización: Gráfica circular mostrando el porcentaje de supervivencia por género.*

### 🛳️ Supervivencia por Clase
- **Primera Clase:** 62.9%
- **Segunda Clase:** 47.2%
- **Tercera Clase:** 24.2%

*Visualización: Gráfica de barras horizontales mostrando la supervivencia por clase.*

### 💰 Análisis de Tarifas
- **Conclusión:** Las tarifas más altas mostraron una mayor tasa de supervivencia.

*Visualización: Gráfica de barras mostrando las tasas de supervivencia por cuartil de tarifa.*

### 👶👦👩👨👴 Supervivencia por Grupo de Edad y Clase
- **Niños:** Los niños en primera clase tuvieron las tasas de supervivencia más altas.
- **Adolescentes:** La tasa de supervivencia varía notablemente entre clases.
- **Adultos Jóvenes y Adultos:** La clase sigue siendo un factor determinante, con mayores tasas de supervivencia en clases superiores.
- **Mayores:** Los adultos mayores en primera clase también muestran una ventaja significativa en supervivencia.

*Visualización: Subgráficas mostrando el porcentaje de supervivientes en cada clase por grupo de edad.*

### 👪 Familias Completas
- **Número total de familias por clase:**
  - **Primera Clase:** 184 familias
  - **Segunda Clase:** 161 familias
  - **Tercera Clase:** 400 familias
- **Familias completas que sobrevivieron:**
  - **Primera Clase:** 104 familias supervivientes
  - **Segunda Clase:** 62 familias supervivientes
  - **Tercera Clase:** 95 familias supervivientes

*Visualización: Gráfica de barras horizontales mostrando el número total de familias y las familias completas que sobrevivieron por clase.*

#### Porcentajes de Supervivencia por Clase
- **Primera Clase:** 56.5%
- **Segunda Clase:** 38.5%
- **Tercera Clase:** 23.8%

## 💡 Conclusiones
- **Impacto del Género:** Las mujeres tuvieron una mayor tasa de supervivencia, reflejando las políticas de rescate que priorizaron a mujeres y niños.
- **Impacto de la Clase:** La clase socioeconómica influyó significativamente en las probabilidades de supervivencia, con tasas más altas para los pasajeros de primera clase.
- **Tarifas Pagadas:** Las tarifas más altas se correlacionaron con mayores tasas de supervivencia, posiblemente debido al acceso a mejores ubicaciones y recursos.
- **Supervivencia Familiar:** Un número limitado de familias completas sobrevivió, con una mayor representación en las clases más altas.

Este análisis proporciona una visión profunda de los factores que afectaron la supervivencia en el Titanic, destacando las desigualdades y dinámicas presentes durante el desastre. Esta información es valiosa para la comprensión histórica y ofrece lecciones importantes para mejorar las políticas de seguridad en situaciones de emergencia.

---

¡Este análisis nos permite desentrañar la complejidad de los eventos que ocurrieron a bordo del Titanic, revelando patrones que influyeron en la supervivencia de los pasajeros! 🚢📊

License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the license terms.
Contact

For any inquiries or suggestions, please reach out to:

    Name: Sergio Iglesias Varela
    Email: sergioiglesiasvarela1986@gmail.com
    LinkedIn: https://www.linkedin.com/in/sergio-iglesias-varela-586265109/
    GitHub: https://github.com/sergioiglevar

