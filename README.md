# user-service-api-with-docker

Este repositorio contiene una API implementada utilizando Docker para facilitar la configuración del entorno de desarrollo y despliegue de la aplicación.

## Requisitos previos
- Docker: Asegúrate de tener Docker instalado en tu sistema antes de continuar.

## Instrucciones de Uso

### Clonar el repositorio
Clona este repositorio en tu máquina local usando el siguiente comando:

```
git clone https://github.com/myselfcarvajal/user-service-api-with-docker.git
```

### Usando Docker para la API

1. Construir la imagen de Docker:
```
docker build -t user-sevice-api:latest .
```

2. Ejecutar el contenedor de Docker:
```
docker run --name user-api -d -p 3000:3000 user-sevice-api:latest
```


### Acceder a la API

Una vez que la API esté en funcionamiento, puedes acceder a ella a través de la siguiente URL:
```
http://localhost:3000
```


## Contribuir
Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Crea un fork del repositorio
2. Crea una rama para tu nueva funcionalidad (git checkout -b nueva-funcionalidad)
3. Haz los cambios necesarios y commitea los cambios (git commit -m "Agrega nueva funcionalidad")
4. Sube los cambios a tu fork (git push origin nueva-funcionalidad)
5. Crea un pull request en este repositorio para revisar los cambios.