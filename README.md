# lab01-iac-miercoles

Tenemos codigo de aplicacion web. Se compone de un archivo HTML que tiene como contenido WEB01

Quiero poder publicar esta web, especificamente una sola copia como primera instancia.

TAREA:
- Desplegar dos web. Deben ser WEB01 y WEB02
- Los puertos configurados deben ser 4000 y 4001
- Gestionar carpetas
- Hacer uso de gitflow/conventional commits.

COMANDOS PARA EJECUTAR:

````
WEB 01
#docker build -t web01 .
#docker run --name test3 -p 8080:4000 web01
````

````
WEB 02
#docker build -t web02 .
#docker run --name test4 -p 8081:4001 web02
````