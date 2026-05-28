# Monitoreo de Exportaciones de Uruguay: Concentración y Destinos Estratégicos

Dashboard interactivo en Power BI para el análisis de la inserción internacional y diversificación de mercados de Uruguay, utilizando datos oficiales de comercio exterior.

## Descripción del Proyecto
Este tablero fue diseñado para evaluar la estructura exportadora del país y el nivel de riesgo ante la concentración de mercados. El análisis se enfoca en las dinámicas institucionales y el posicionamiento estratégico frente a los principales bloques económicos globales.

##  Características del Backend y Modelo de Datos
Este proyecto prioriza las buenas prácticas de arquitectura en Power BI:
* **Centralización de Métricas:** Almacenamiento de todas las expresiones en una tabla pura de medidas (`_Medidas`).
* **Optimización de Rendimiento:** Desactivación de la inteligencia de tiempo automática para garantizar un modelo ligero y eficiente.
* **Control Temporal Eficiente:** Manejo de orden cronológico personalizado para la segmentación de datos mensuales sin sobrecargar el motor DAX.

## Métricas Clave Implementadas (DAX)
* **Índice Herfindahl-Hirschman (HHI):** Calculado dinámicamente sobre la cuota porcentual de exportaciones por mercado destino para medir el nivel de diversificación o vulnerabilidad (< 1500: Diversificado, > 2500: Concentrado).
* **Participación por Bloque y Régimen:** Apertura analítica que contrasta el volumen operado en Aduana Directa (AD) frente a Zonas Francas (ZF).
![Dashboard Hoja 1](https://github.com/rodrigoferetti/Uruguay-Comercio-Exterior-Dashboard/blob/main/Vision%20General.PNG?raw=true)
![Dashboard Hoja 2](https://github.com/rodrigoferetti/Uruguay-Comercio-Exterior-Dashboard/blob/main/Enfoque%20Geopolitico.PNG?raw=true)
