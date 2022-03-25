# FacturadoraDocker

Proyecto de una facturadora sencilla, que se enfoca en la orquestación de contenedores  con Docker compose en dos entornos diferentes (PRE y PROD), implementando múltiples instancias. Este proyecto está realizado en un back-end de Spring Boot y un front-end de Angular. 

## Requisitos para realizar la instalación de la orquestación
Es necesario tener instalada en la maquina docker Engine y colocar los siguientes comandos:

 El siguiente comando es necesario para la construcción de los contenedores:
        
    $> docker-compose -f stack-billing.yml build --no-cache
    
 El siguiente comando es necesario para inicializar los contenedores en docker:
 
    $> docker-compose -f stack-bulling.yml up -d --force-recreate
    
   
