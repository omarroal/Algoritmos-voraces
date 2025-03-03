# Algoritmos-voraces

Un procesador debe atender n procesos. Todos los procesos llegan al mismo tiempo al sistema y tienen
tiempos de ejecución t1,...,tn, respectivamente. Se quiere ejecutar los procesos de forma que se minimice el
tiempo total de permanencia en el sistema de todos los procesos. El tiempo de permanencia de un proceso
en el sistema es el tiempo transcurrido desde que el proceso entra en el sistema hasta que finaliza su
ejecución.

Por ejemplo, para un sistema con n=3 procesos cuyos tiempos de ejecución son t1=7, t2=3 y t3=4, si se ejecuta
primero el proceso 1, luego el 2 y finalmente el 3, el tiempo de permanencia del primer proceso será 7, el del
segundo proceso 7+3 y el del tercer proceso 7+3+4, con lo cual el tiempo total de permanencia en el sistema
de todos los procesos es 31. Este tiempo puede cambiar según cuál sea el orden en que se ejecutan los
procesos. Para este ejemplo el tiempo mínimo de permanencia total es 24.

Parte I:
Crea un programa que pida por teclado el número total de procesos y sus tiempos de ejecución, y proporcione
cuál es el tiempo mínimo total de permanencia en el sistema de todos los procesos y el orden en que deben
ejecutarse. Todos los valores son números enteros.
El formato de entrada y salida del programa se encuentra en el corrector online.

Parte II:
Una vez aceptado el programa de la Parte I por el corrector, crear una versión extendida del mismo que
imprima por pantalla una traza similar a las que se utilizan en teoría para visualizar la ejecución de los distintos
algoritmos. El formato de la traza es libre, pero debe mostrar el estado de las distintas variables que forman
parte del algoritmo cuando son modificadas, así como el nombre de la función a las que pertenecen.
Adjuntar capturas de pantalla de la traza para un ejemplo de entrada. Esta versión extendida del programa
no debe ser subida al corrector.
