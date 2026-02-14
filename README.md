# Análisis de ventas con Python y SQL

## Contexto del proyecto
Este proyecto tiene como objetivo analizar datos transaccionales de ventas para identificar patrones de ingresos, países con mayor rendimiento y métricas clave de negocio.

Se simula un flujo de trabajo real de análisis de datos combinando Python, SQL y visualización.

## Objetivo
Construir un análisis exploratorio y de negocio utilizando un dataset real de ventas, integrando:

- Limpieza de datos
- Almacenamiento en base de datos
- Consultas SQL
- Visualización de resultados

## Herramientas utilizadas
- Python
- Pandas
- SQLite
- SQL
- Matplotlib
- VS Code

## Proceso de trabajo

### 1. Carga de datos
Se importó un archivo Excel con transacciones de ventas.

### 2. Limpieza de datos
Se eliminaron:
- Cantidades negativas
- Precios en cero
- Clientes nulos

### 3. Creación de base de datos
Se creó una base SQLite y se almacenó la tabla limpia.

### 4. Análisis SQL
Se realizaron consultas para obtener:

- Revenue por país
- Revenue total
- Ticket promedio
- Productos más vendidos
- Periodo temporal del dataset

### 5. Visualización
Se generó una gráfica de revenue por país.

## Hallazgos principales
- Reino Unido concentra la mayor parte de los ingresos.
- Existe alta concentración de ventas en pocos países.
- Se identificaron productos líderes en revenue.
- Se calcularon métricas clave de negocio.

## Habilidades demostradas
- Limpieza de datos con Python
- Creación de base SQLite
- Consultas SQL reales
- Métricas de negocio
- Visualización de datos
- Organización de proyecto en GitHub

## Estructura del proyecto

sales-analysis-sql-python/
│
├── data/
├── database/
├── notebooks/
│ ├── 01_data_loading.ipynb
│ └── 02_sql_analysis.ipynb
│
├── images/
└── README.md

## Próximas mejoras
- Dashboard interactivo
- Análisis por cliente
- Análisis temporal de ventas
