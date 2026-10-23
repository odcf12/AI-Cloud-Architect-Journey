# Semana 1 - Docker Fundamentals

## Conceptos aprendidos

### Imagen

Una imagen es una plantilla que contiene una aplicación y todas sus dependencias.

### Contenedor

Un contenedor es una instancia en ejecución creada a partir de una imagen.

### Docker Hub

Docker Hub es un repositorio público donde se almacenan imágenes Docker.

## Comandos utilizados

### Verificar instalación

```bash
docker --version
docker info

Ejecutar primer contenedor
Shell
docker run hello-world
Ejecutar nginx
Shell
docker run -d -p 8080:80 nginx
Ver contenedores
Shell
docker ps
docker ps -a
Detener y arrancar contenedores
Shell
docker stop <container_id>
docker start <container_id>
Lecciones aprendidas
Una imagen no es un contenedor.
Un contenedor vive mientras su proceso principal esté ejecutándose.
docker run crea y arranca un contenedor.
docker start reutiliza un contenedor existente.
Las imágenes descargadas se almacenan localmente y se reutilizan.