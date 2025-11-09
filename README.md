📊 Análisis de Rendimiento y Recomendación de Venta de Tiendas

🎯 Objetivo del Proyecto

Este proyecto se centra en realizar un análisis de datos exhaustivo de cuatro tiendas minoristas (tienda, tienda2, tienda3, tienda4) para determinar su rendimiento operativo, rentabilidad y nivel de satisfacción del cliente.

El objetivo final es sintetizar los hallazgos para recomendar al Sr. Juan qué tienda debería vender y cuál debería conservar, basándose en una justificación clara y objetiva de los datos.

📈 Análisis Realizados

Se generaron análisis y visualizaciones utilizando la librería Pandas y Matplotlib para evaluar los siguientes indicadores clave de rendimiento (KPIs):

Ingresos Totales: Se calculó el ingreso total de ventas por cada tienda para determinar su volumen de negocio.

Costo de Envío Promedio: Se analizó el costo promedio de envío por tienda, un factor crítico que impacta el margen de beneficio y la competitividad.

Satisfacción del Cliente: Se evaluó la calificación promedio de los clientes por tienda.

Tendencias de Producto: Se identificaron las combinaciones de Producto y Calificación más y menos frecuentes para detectar problemas de calidad o productos estrella.

Distribución Geográfica: Se mapearon las ventas utilizando latitud y longitud (lat, lon) para identificar áreas de alta concentración de ventas (clústeres geográficos).

📁 Estructura de Archivos

Archivo

Descripción

informe_final_venta.md

Documento que sintetiza todos los hallazgos y presenta la recomendación final de venta (Tienda2) con una justificación respaldada por datos.

analisis_geografico_ventas.py

Script de Python que realiza la concatenación de los DataFrames y genera el gráfico de dispersión/mapa de calor para visualizar la concentración geográfica de las ventas.

guia_github.md

Documento de apoyo con instrucciones sobre cómo configurar y mantener este proyecto en GitHub.

README.md (este archivo)

Introducción y resumen del proyecto.

🛠️ Ejecución del Análisis Geográfico

El archivo analisis_geografico_ventas.py contiene el código para generar el mapa de ventas geográficas. Para ejecutarlo:

Asegúrate de que los DataFrames individuales (tienda, tienda2, etc.) estén cargados en tu entorno.

Asegúrate de tener instaladas las librerías pandas y matplotlib.

Ejecuta el script:

python analisis_geografico_ventas.py


💡 Conclusión Principal

Basado en el análisis de ingresos y riesgos, se recomienda al Sr. Juan VENDER la Tienda2. Aunque esta tienda genera el mayor ingreso absoluto, sufre de la calificación de cliente más baja y el costo de envío más alto, lo que representa un alto riesgo operacional para la retención. Por otro lado, se recomienda CONSERVAR la Tienda4, por su excelente equilibrio entre altos ingresos y alta satisfacción del cliente.

Proyecto generado como parte de un análisis de datos y recomendación estratégica.
