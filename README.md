# Resumen del Proyecto
Este proyecto consiste en un análisis exhaustivo del comportamiento de compra de los usuarios de Instacart. A través del procesamiento de grandes volúmenes de datos transaccionales, se identificaron patrones temporales, productos de alta fidelización y fricciones en el embudo de compra (UX) con el fin de proponer estrategias de marketing digital y optimización de ingresos.

# Metodología y Preparación de Datos
El análisis se basó en la integración de 5 datasets críticos: Comercio, Clientes, Facturación, Productos y Catálogos.

Data Cleaning: Se ejecutó un proceso de limpieza profunda eliminando duplicados en IDs clave y tratando valores ausentes.

Consistencia: Validación de tipos de datos, especialmente en estampas de tiempo (timestamps) y variables categóricas para asegurar la integridad de las pruebas estadísticas.

# Análisis Exploratorio y Hallazgos (EDA)
1. Detección de Anomalías y UX
Se identificaron comportamientos atípicos que sugieren oportunidades de mejora técnica:

Patrones Nocturnos: Compras a las 2:00 AM los miércoles, lo que abre una investigación sobre errores de sistema o segmentos de nicho.

Fricción en el Checkout: Detección de carritos con valores nulos, identificados como un indicador crítico de fricciones en la experiencia de usuario (UX).

2. Drivers de Fidelización
Se analizó el Top 20 de artículos con mayor tasa de recompra para entender qué productos retienen al cliente.

Estrategia: Clasificación por margen de contribución para facilitar tácticas de Cross-selling y Upselling.

3. Patrones Temporales
El análisis reveló que el miércoles al mediodía es el punto máximo de actividad en carritos de compra.

# Aplicaciones Estratégicas (Business Impact)
Basado en los hallazgos, se proponen las siguientes líneas de acción:

Dynamic Pricing & Promos: Activación de descuentos dinámicos en franjas horarias de baja actividad para balancear la carga operativa.

Aumento del Ticket Promedio: Implementación de bundles (paquetes) de productos asociados basados en la afinidad de categorías.

Remarketing Inteligente: Rediseño de estrategias de comunicación push para acortar el ciclo de recompra en segmentos específicos.

Personalización: Segmentación de clientes basada en hábitos de frecuencia para experiencias de compra a medida.

# Tecnologías Utilizadas
Python: Pandas, NumPy.

Visualización: Matplotlib / Seaborn.

Análisis Estadístico: Segmentación de usuarios y análisis de series temporales.
