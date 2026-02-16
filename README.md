# Análisis de Presupuestos Familiares y Renta Regional (2022-2024)

## Descripción del Proyecto
Este proyecto de TFM realiza un análisis avanzado del comportamiento de gasto de los hogares españoles. La investigación integra microdatos de la **Encuesta de Presupuestos Familiares (EPF)** con indicadores macroeconómicos de **Renta Media por CCAA** extraídos del INE.

El objetivo principal es identificar patrones de consumo, disparidades regionales y la correlación entre la riqueza de una comunidad y el gasto real de sus ciudadanos.

## Estructura del Repositorio
* `data/raw/`: Microdatos originales de la EPF (2022-2024) y Excel de Renta.
* `data/processed/`: Dataset maestro final optimizado para visualización.
* `notebooks/`: Jupyter Notebook con el proceso ETL, limpieza y análisis exploratorio (EDA).
* `dashboard/`: Dashboard interactivo en Excel con KPIs y segmentadores.
* `docs/`: Informe explicativo detallado del análisis.

## Tecnologías Utilizadas
* **Python 3.10+**: Pandas, Numpy (ETL), Matplotlib y Seaborn (Visualización).
* **Jupyter Notebook**: Entorno de desarrollo.
* **Excel**: Power Query y Tablas Dinámicas para el Dashboard final.

## Principales Hallazgos
* **Volumen de Gasto:** Madrid y Cataluña lideran el gasto total nacional, seguidas por Andalucía, debido a su peso demográfico.
* **Eficiencia de Ahorro:** Se identifica al **País Vasco** como un valor atípico estratégico: alta renta per cápita con un gasto contenido, sugiriendo una mayor tasa de ahorro.
* **Correlación:** Se confirma una relación directa positiva entre la renta disponible regional y la capacidad de gasto de los hogares.

## Instrucciones de Instalación
1. Clonar el repositorio.
2. Instalar dependencias: `pip install pandas openpyxl matplotlib seaborn`
3. Ejecutar el notebook de la carpeta `notebooks/` para regenerar el dataset.

4. ---
## 📂 Acceso a los Datos
Debido a que los microdatos originales de la Encuesta de Presupuestos Familiares (EPF) y Renta Regional superan el límite de almacenamiento de GitHub (>100MB), no se han incluido en este repositorio.

Puedes obtener los datasets originales en los siguientes enlaces oficiales del INE:
* [Microdatos EPF - Instituto Nacional de Estadística](https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176806&menu=resultados&idp=1254735976607)
