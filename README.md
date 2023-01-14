# Actividad-18-cc3s2
Actividad 18 del curso de Desarrollo de Software CC3S2
# Instalación de Docker
En mi caso instalé Docker para Windows utilizando WSL y además, también instalé Docker Desktop

# Ejecutando hello-world
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/18-docker-hello-world.PNG "")

# Imágenes y contenedores Docker
Una imagen es un bloque de construcción sin estado. Lo puedes ver como una colección de todos los archivos para ejecutar tu aplicación. Y un contenedor es una instancia en ejecución de una imagen.

# Creación de imágenes de Docker
# Docker commit
- Ejecuta un contenedor desde ubuntu y lo conectamos a la línea de comando e instalamos el kit de herramientas de git:
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/ubuntu-apt-get.PNG "")
- Verificamos qué ha cambiado en el contenedor
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/docker-diff.PNG "")
- Hacemos commit el contenedor a la imagen
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/docker-commit.PNG "")
- Listamos las imágenes
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/docker-images.PNG "")
- Luego, creamos un contenedor a partir de la imagen creada
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/docker-run-container.PNG "")

# Dockerfile
1. Crear nuevo directorio y un archivo llamado Dockerfile
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/dockerfile-ubuntu.PNG "")
2. Ejecutamos el comando para construir la imagen utilizando el archivo Dockerfile
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/dockerfile-image.PNG "")
3. Comprobamos que la imagen se creó ejecutando el sgte comando:
![Alt text](https://raw.githubusercontent.com/ricardoolivaresventura/ExamenFinalCC-3S2/main/dockerfile-images-docker.PNG "")
