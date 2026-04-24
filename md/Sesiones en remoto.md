# SESIONES 

Para revisar las sesiones que se encuentran activas o verificar el estatus de cada usuario se realiza el siguiente procedimiento:

1. Ingresar al escritorio remoto

![Escritorio remoto](/img/remoto.png)

2. Posteriormente ingresar a CMD o Powershell pero como administrador. 

![Escritorio remoto](/img/sesiones1.png)

3. Al ingresar y estar en la terminal se ocupa el sigueinte comando para ver las sesiones que se tienen:

    **query sessions**

4. Como podemos observar en la siguiente imagen al ingresar el comando nos muestra los usuarios que se encuentran en el servidor, junto con informacion relacionada al usuario como:

* NOMBRE DE LA SESION
* NOMBRE DE USUARIO
* ID
* ESTADO
* TIPO
* DISPOSITIVOS

![Escritorio remoto](/img/sesiones2.png)
___

## DOBLE SESION

Algunos usuarios crean doble sesion, pues no cierran alguna sesion y abren otra en algun otro equipo / dispositivo, por lo que es importante que se cierre una sesion para evitar problemas de saturacion de memoria del servidor.

En estos casos es i