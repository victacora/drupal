# drupal
Ejecutar este comando para descargar las imagenes y subir los contenedores
- docker compose up -d

Despues de subir los contenedores
docker compose exec drupal bash

Despues de configurar los volumenes, descargar drupal en el contenedor
- composer create-project drupal/recommended-project .

Solucionar errores durante la instalacion

- cp web/sites/default/default.settings.php  web/sites/default/settings.php
- chmod -R 777 web/sites/default/settings.php

- mkdir web/sites/default/files
- chmod -R 777 web/sites/default/files

Para iniciar la instalacion
http://localhost:8081/

Adminer
http://localhost:8080/?server=db&username=drupal&db=drupal
