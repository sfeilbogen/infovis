# Medios de transporte

![google_maps](https://github.com/sfeilbogen/infovis/blob/gh-pages/googlemaps.png)


 
**Descripción:**
En base a Google Calendar del mes de julio y agosto y utilizando Google Maps recolecté los eventos realizados y el medio de transporte que utilicé tanto para ir como para volver del mismo a mi dirección. Analicé qué tipo de actividad es (amigos, familia, dentista, shabat, varios), la fecha del evento, en que momento del día lo realicé (mañana/tarde/noche), su dirección y latitud y longitud. 

DATOS CRUDOS COLUMNAS
Los datos crudos fueron subidos en un .csv. En columnas se encuentra: 
* Actividad	
* Medio de transporte	
* Momento del dia	
* Dia	
* Mes	
* Año	
* Fecha	
* Lugar	
* Distancia desde mi casa (en metros)	
* Tiempo del recorrido (en minutos)	
* Latitud 	
* Longitud												


Realice 5 visualizaciones:

*Visualización 1:* Maximas distancias recorridas por medio de transporte
BARAS HORIZONTALES
Realice un grafico de barras horizontales para visualizar según el medio de transporte cuales fueron las maximas distancias recorridas del mismo junto a que tipo de actividades fueron. Agregue de la sección de análisis el promedio y una linea constante. 
En las filas se diferencia en medio de transporte y tipo de actividad y en las columnas las maximas distancias recorridas desde mi casa.

*Visualización 2:* Distancias recorridas por dirección con medio de transporte. 
MAPA DE SIMBOLOS
Realice un mapa de simbolos marcando las direcciones de las muestras, en tamaño diferencio por distancia respecto a mi casa (mientras más lejos mas grande el simbolo), en color agrego el medio que fue utilizado para llegar al destino y en etiqueta marco las direcciones. Marco tambien donde se encuentra mi casa para poder tomar dicha dirección como referencia al origen. En columnas estableci la longitud, en filas la latitud.

*Visualización 3:* Tiempos totales por medio de transporte y momento del día.
Realice una visualización de caja y bigotes. Segun el tiempo del recorrido en suma establecido en las filas y el momento del dia (dia, tarde, noche) (establecido en las columnas). En etiquetas establecí el medio de transrpote para asi poder ver si se encuentran datos atipicos en la muestra y ver los tiempos utilizados totales por medio y momento del día. 

*Visualización 4:* Medio mas utilizado por semana.
Con el fin de poder analizar que medio fue utilizado más por semana realice un grafico circular. En semanas estableci la fecha con una funcion tomanto la semana, en etiqueta y en color establecí el medio de transporte y en ángulo un recuento distinto de medio de transporte.


Para hacer la visualizacoin final hice un dashboard o historia agregando maximos o minimos pertinentes al grafico 
