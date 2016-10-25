# EVENT LOOP.
---

Su trabajo es revisar el stack, si el stack está vacío toma la primera instrucción de queue y la introduce en el stack, sonde se ejecuta inmediatamente.

**JavaScript**
Es un lenguaje de programación de un sólo hilo, lo que significa que sólo tiene un stack que es lo mismo a que sólo puede hacer una cosa a a la vez.

El lenguaje javascript cuenta con un componente llamado *call stack*, que se encarga de llevar el control de en qué parte de ejecución está el programa. Asi, si hay saltos a funciones, sabe exactamente a dónde regresar para seguir ejecutantdo.

Javascript corre en un navegador, que ofrece un entorno de runtime (como V8), web APIs, callback queue, event loop; todo esto para que javascript pueda "ejecutar más de una instrucción a la vez."

Cuando no se maneja un event loop el navegador tiene que esperar a hacer todas las peticiones o instrucciones ára poder realizar otras tareas, como renderizar imágenes o actualizar la vista de un botón. En otras palabras, el event loop sirve para lidiar con el *blocking*(que no es más que código que su ejecución es lenta).

**Asíncronía**
Permite al navegador ejecutar las instrucciones en tiempos determinados, por ejemplo al utilizar la función *setTimeout*.
Callback es básicamente código que corremos y al darle un **callback** ese código se corre después.

La sincrónía es el método tradicional de JS, se refiere a ejecutar las instrucciones en orden y una instrucción por vez. En esto existe el problema de Blocking, que se refiere a c+odigo de lenta ejecución, que ya corriendo en un navegador puede hacer la experiencia del usuario muy cansada y tediosa.





