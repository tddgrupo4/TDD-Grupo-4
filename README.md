# Equipo 4

## Nombre de miembros del equipo

Daniel Leonardo Romero

Juan Miguel Cabrera

## Solución
API que ofrezca información del tiempo en un formato más cercano al lenguaje natural que a la visualización de datos (grados ºC, precipitación en mm...)

Dadas las dificultades que estamos teniendo para arrancar, mejor dejar un objetivo muy acotado y dejar a un lado posibles extensiones de funcionalidad.

API externa desde la que consumir datos meteorológicos: https://www.metaweather.com/api/
- Otras alternativas: https://github.com/public-apis/public-apis#weather

## Tecnología
 - Lenguaje: Java (jdk 15)
 - Framework: Spring Boot 2.4.3.
 - Logging: Aprovechando el uso de la biblioteca de "_azúcar sintáctico_" [lombok](https://projectlombok.org/features/log) se podrán utilizar cualquiera de las herramientas de _logging_ incluidas ([org.slf4j.Logger](http://www.slf4j.org/api/org/slf4j/Logger.html), [com.google.common.flogger.FluentLogger](https://google.github.io/flogger/)...)
 - Almacenamiento: Actualmente no consideramos contar con un servicio de persistencia sino realizar toda la operativa _on the fly_
 -  Configuración remota: Sin definir por el momento.
