# PROYECTO-EASY-LOANS-2023-TABLEU---UCM
Dashboard en Tableau sobre operaciones de préstamos (Easy Loans)

# Easy Loans — Dashboard Tableau (Operaciones 2023)

Proyecto académico de Business Intelligence con Tableau para analizar las operaciones de préstamos de **Easy Loans** durante 2023 y extraer insights para apoyar decisiones de negocio.

## Enlace al dashboard
- Tableau Cloud: https://us-west-2b.online.tableau.com/t/ucm2024/views/Easy_Loans_operaciones_2023_PABLO_URRA_SALAS/DASHBOARDFINAL?:origin=card_share_link&:embed=n

## Objetivo del proyecto
Construir un dashboard interactivo que permita explorar tendencias, comportamiento de los préstamos y posibles riesgos operativos, con visualizaciones claras y orientadas a stakeholders.

## Dataset y modelo de datos
- Fuente de datos: `Easy-Loans-Operaciones-2023.xlsx`.
- Tablas: `Orders`, `Refunds`, `Merchant`.
- Modelado: relaciones entre tablas en Tableau.
- Alcance geográfico: operaciones en tiendas europeas (excluyendo Marruecos).

## Métricas y cálculos implementados (Tableau)
- Promedio del importe de préstamos.
- Máximo y mínimo del importe.
- Conteo de comercios.
- Conteo de reembolsos.
- Valor acumulado (running sum).
- Promedio total fijo (LOD FIXED).

## Interactividad requerida
- Parámetro: **Valor Préstamo Mínimo** para filtrar operaciones por un umbral definido por el usuario.
- Filtros globales: país (selector), rango de fechas y filtro “Préstamo Mínimo” (True).
- Acción de dashboard: al seleccionar un país en el mapa, se resaltan/filtran el resto de visualizaciones.

## Visualizaciones del dashboard
- Tabla de KPIs.
- Mapa por país coloreado por el promedio del préstamo.
- Área acumulada por día (valor acumulado) segmentada por país.
- Vista de desviación: operaciones por encima/debajo del promedio.

## Dataset
- Fuente: `data/Easy-Loans-Operaciones-2023.xlsx`

## Contenido del repositorio
- `data/`: dataset

## Calificación
- Nota: **9,0/10**
- Evaluación: agosto 2025

## Feedback del profesor (resumen)
**Puntos fuertes**
- Implementación técnica sólida y alineada con los objetivos del análisis crediticio.
- Dashboard con estructura clara, navegación coherente y KPIs bien planteados.
- Mapa con codificación por color adecuada y gráfico temporal útil para ver la evolución.

**Aspectos a mejorar**
- El gráfico de desviación necesita una ordenación correcta para facilitar la comparación e interpretación.
- Los filtros no se aplican de forma consistente a todas las vistas (p. ej., país solo afecta al mapa y fecha solo al área), lo que fragmenta la experiencia.

**Siguiente mejora prevista**
- Unificar filtros globales (país y fecha) para que afecten a todo el dashboard y ajustar el orden del gráfico de desviación.
