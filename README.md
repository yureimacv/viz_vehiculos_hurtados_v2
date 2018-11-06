# viz ¿Pensado en comprar carro? Versión 2.0

La visualización: [Robo de vehículos en Colombia](https://public.tableau.com/profile/yureimacv#!/vizhome/RobodevehculosenColombiaV2_0/Dashboard1?publish=yes)


# *FRAMEWORK TAMARA*

## WHAT
DATASET y ATRIBUTOS:
El tipo de  es una TABLA TEMPORAL con los siguientes atributos:
  * Fecha: Atributo que describe la fecha de robo del vehículo. Tipo: Cuantitativa secuencial.
  * Marca: Referencia o marca del vehículo. Tipo: Categórica.
  * Línea: Referencia específica (depende de la marca). Tipo: Categórica.
  * Modelo: Modelo del vehículo robado. Tipo: Categórica.
  * Municipio: Ciudad en donde se presentó el robo. Tipo: Categórica.
  * Departamento: Departamento donde se presentó el robo. Tipo: Categórica.
  * Color: Color del vehículo. Tipo: Categórica.
  * Número de registros: Atributo derivado que indica el total del número de registros. Cuantitativo – Secuencial.
  * Arma empleada: Modalidad en que se realizó el robo del vehículo. Tipo: Categórica.

## WHY	
TAREA PRINCIPAL	
  * Comparar tendencias y similitudes sobre los vehículos por marca que han sido hurtados en los últimos 3 años. [COMPARE       TRENDS].

TAREAS SECUNDARIAS
  * Identificar caracteristicas de color de los vehículos robados. [IDENTIFY FEATURES]
  * Identificar las ciudades en las roban con mayor frecuencia una marca de vehiculo específico. [BROWSE DISTRIBUTION]
  * Identificar la frecuencia de modalidad más frecuentes para la marca de un vehiculo. [IDENTIFY FEATURES]
  * Construir la variable que representa el total de los registros [DERIVE FEATURES]
  
## HOW
  * Visualización: LINE CHART
    Diagrama con marcas de línea que representan el número de vehículos robados en cada año por mes. Se realiza la    representación de los meses (HORIZONTAL POSITION) y el número de registros de vehículos robados (VERTICAL POSITION) (ENCODE EXPRESS). Se plantea un FACET SUPERIMPOSE con característica diferenciadora basada en el COLOR HUE para cada uno de los años representados, este busca hacer la comparación 
  
  * Visualización: STACKED CHAR – Desempeño
Se basa en marcas de línea expresando el valor de la sumatoria de los registros de vehículos robados en el eje Y, con barras separadas en el eje X por la categoría modelo con código de tamaño de altura por el valor del atributo año. [ENCODE-EXPRESS, SEPARATE-ORDER-ALIGN]

  * Visualización: TREE MAP – Municipio
Expresa por tamaño de áreas el número de registros de vehículos hurtados registrados, en cada municipio por estructura jerarquica del departamento a donde corresponde. [ENCODE-EXPRESS, ENCODE-SEPARATE-ORDEN-ALIGN]

  * Visualización: Bar Chart – Color
Se basa en marcas de línea expresando el número de registros de vehículos hurtados registrados en el eje X, con alineación en la posición espacial horizontal, separadas por el atributo (COLOR) con la posición espacial vertical ordenada descendentemente por frecuencia. [ENCODE-EXPRESS, ENCODE-SEPARATE-ORDEN-ALIGN]

  * Visualización: Bar Chart – Arma empleada
Se basa en marcas de línea expresando el número de registros de vehículos hurtados registrados en el eje X, con alineación en la posición espacial horizontal, separadas por el atributo (ARMA EMPLEADA) con la posición espacial vertical ordenada descendentemente por frecuencia. [ENCODE-EXPRESS, ENCODE-SEPARATE-ORDEN-ALIGN]

# INSIGHTS
 * Esta herramienta es muy útil para tomar medidas de seguridad con los vehiculos propios (o que se planean sean propios), en terminos de: en qué lugares se debe tener más precaucion, si un vehículo es frecuentemente usado en el servicio publico como el SPARK, si la frecuencia de modalidad de robo de un vehiculo es a mano armada, o por cual color del carro puedo correr mayor riesgo.
 * El hurto de vehiculos ha aumentado en 2018 con respecto a los 3 años anteriores registrados.
 * En mayor cantidad los vehiculos hurtados son de color blanco, una suposicion personal es porque son mas fáciles de pintar de otro color o porque muchos de ellos son de servicio publico por ende tienen mayor demanda de repuestos. 
 * Algunos vehiculos de modelos anteriores son apetecidos por los ladrones debido a que ciertas marcas como los Mazda 323 son “embellecidos” y se requieren repuestos o “mejoras” a la carroceria del vehículo. 
 * Se percibe que los vehículos que con mayor frecuencia son robados por llave maestra son más inseguros y si una persona tiene un vehículo de este tipo lo mejor seria no dejarlo parqueado en la calle.


## DATOS TOMADOS

Se tomaron los datos de la base publica Datos Abiertos:
  https://www.datos.gov.co/Seguridad-y-Defensa/Delito-Hurto-Automotores/fapc-qe8b/data .
  https://www.datos.gov.co/Seguridad-y-Defensa/Hurto-de-Automotores-2016/4ypz-vzzw/data .
  https://www.datos.gov.co/en/Seguridad-y-Defensa/Hurto-de-automotores-2017/ng7s-tz8p/data .
  https://www.datos.gov.co/Seguridad-y-Defensa/Hurto-de-automotores-2018/q8g6-3xwv/data .
  
## TECNOLOGÍAS UTILIZADAS

Tableau


@Yureimacv
