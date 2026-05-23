# 📊 Data Science: Análisis Explorador y Minería de Datos con MongoDB

Proyecto integral de exploración, limpieza y análisis de grandes volúmenes de datos utilizando Python, Pandas y MongoDB. Se implementa un pipeline completo de data science, desde la carga inicial hasta la identificación de patrones y anomalías en datasets complejos.

## 🎯 Objetivos

- **Cargar y explorar** estructuras de datos de múltiples fuentes (CSV, bases de datos)
- **Limpiar datos** identificando valores nulos, duplicados y rangos atípicos
- **Normalizar y preprocesar** variables para análisis posterior
- **Implementar análisis exploratorio** (EDA) para descubrir patrones y correlaciones
- **Integrar MongoDB** como sistema de almacenamiento y consulta de datos estructurados
- **Generar hallazgos significativos** derivados del análisis de datos

## 🧠 Conceptos Clave

- **Python**: Lenguaje de programación principal
- **Pandas & NumPy**: Manipulación y análisis de datos
- **MongoDB**: Base de datos NoSQL para almacenamiento flexible
- **Matplotlib & Seaborn**: Visualización de datos
- **Jupyter Notebook**: Desarrollo interactivo
- **Data Cleaning**: Tratamiento de datos faltantes y anomalías
- **Exploratory Data Analysis (EDA)**: Descubrimiento de patrones

## ⚙️ Desarrollo

### Metodología
Se sigue un enfoque iterativo de ciclo de vida de datos:

1. **Fase 1 - Ingesta y Exploración Inicial**
   - Carga del CSV en estructura de datos
   - Análisis de dimensiones y tipos de datos
   - Identificación de metadatos

2. **Fase 2 - Limpieza y Preprocesamiento**
   - Detección de valores nulos y estrategias de imputación
   - Eliminación de duplicados
   - Detección de outliers y rangos atípicos
   - Normalización de variables

3. **Fase 3 - Análisis Exploratorio (EDA)**
   - Estadísticas descriptivas
   - Análisis de correlaciones
   - Generación de visualizaciones
   - Identificación de relaciones entre variables

4. **Fase 4 - Integración con MongoDB**
   - Almacenamiento estructurado en base de datos
   - Implementación de consultas avanzadas
   - Documentación de esquemas y índices

### Decisiones Importantes
- Uso de MongoDB para garantizar escalabilidad con datos heterogéneos
- Implementación de funciones reutilizables para automatizar el pipeline de limpieza
- Documentación detallada en dos partes de hallazgos (Parte 1 y Parte 2)

## 📊 Resultados

El proyecto genera:
- **Datasets limpios y normalizados** listos para modelado
- **Hallazgos en dos partes**: análisis inicial y análisis avanzado
- **Colecciones MongoDB** con datos integrados y optimizados
- **Visualizaciones exploratorias** que revelan patrones ocultos
- **Documentación completa** de anomalías y decisiones de limpieza

## 🚀 Conclusiones

Este proyecto demuestra la importancia de una fase exploratoria rigurosa antes de cualquier modelado. Los hallazgos obtenidos permiten:

- **Tomar decisiones informadas** sobre ingeniería de características
- **Identificar sesgos** en los datos
- **Validar hipótesis iniciales** con evidencia empírica
- **Preparar datos de calidad** para modelos predictivos

**Mejoras futuras:**
- Implementar perfiles automatizados de data quality
- Crear dashboards interactivos en tiempo real
- Expandir análisis a detección de anomalías con modelos unsupervised

## 📂 Estructura del Proyecto

```
Data Science/
├── RAA-DS-VictorFerrer.ipynb          # Notebook principal con pipeline completo
├── Hallazgos_Parte1_VF.pdf            # Primer análisis de hallazgos
├── Hallazgos_Parte2_VF.pdf            # Análisis profundo y conclusiones
├── Anexos_MongoDB_RAA_DS_VF.pdf       # Documentación de integración MongoDB
└── README.md                          # Este archivo
```

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|-----------|-----|
| **Python 3.x** | Lenguaje principal |
| **Pandas** | Manipulación de DataFrames |
| **NumPy** | Operaciones numéricas |
| **MongoDB** | Base de datos NoSQL |
| **Matplotlib** | Visualización básica |
| **Seaborn** | Visualización estadística |
| **Jupyter Notebook** | Ambiente de desarrollo interactivo |

## ✍️ Autor

**Víctor Ferrer**  
Master en Inteligencia Artificial - UTAMED

---

*Este proyecto forma parte del programa de posgrado en Inteligencia Artificial y demuestra competencias en procesamiento de datos, análisis exploratorio y gestión de bases de datos NoSQL.*
