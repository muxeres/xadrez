# Asignación: Tablero de ajedrez

## Objetivos

* Continuar aprendiendo cómo pasar información de la URL a la ruta
* Practicar enlazar archivos estáticos a plantillas
* Sentirse cómodo al pasar información de la ruta a la plantilla
* Comprender cómo usar un bucle for de forma correcta en la plantilla
* Reconocer el valor de crear un html/css primero y luego agregar lógica/código


Tu programa debe tener la siguiente salida

1. http://localhost:5000: debería mostrar un tablero de ajedrez de 8 por 8
2. http://localhost:5000/4: debería mostrar un tablero de ajedrez de 8 por 4
3. http://localhost:5000/(x)/(y): debería mostrar un tablero de ajedrez de x por y Por ejemplo, http://localhost:5000/10/10 debería mostrar un tablero de ajedrez de 10 por 10. Antes de pasar x y a Jinja, recuerdaprimero convertirlos a enteros (para que puedas usar x o y en un bucle for)
