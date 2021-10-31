## GIMP, editor de imágenes Open Source

Llevaba mucho tiempo con ganas de dar el paso y abandonar Photoshop como editor de imágenes.

La verdad es que después de varios años usándolo tienes cierta dependencia a cualquier software, sea el que sea.
Conoces sus atajos, los truquillos que te hacen todo más fácil, conoces dónde está cada herramienta, cada opción... o al menos las que usas habitualmente.

Y cuando te decides a probar otras opciones la primera sensación es de estar completamente perdido. No sabes dónde está nada, ni cómo se hace tal cosa.
Eres un novato y tardas un siglo en hacer cualquier cosa que tardarías 5 minutos en el otro programa. 

¿Resultado?
Vuelves a Photoshop y sigues como siempre. Unas veces pagando por la subscripción de Adobe y otras..... bueno, todos sabemos cuál es la otra opción.

Pero gracias a que Gimp es open source podemos toquetear y modificar todo lo que queramos, o al menos lo que sepamos.

Y ahí es donde quería llegar. El primer problema que me encontraba es que los atajos de teclado no son los mismos. Y en Photoshop uso mucho los atajos de teclado. "B" para usar el pincel, "Ctrl+T" para transformar, "Ctrl+J" para duplicar una capa, "Ctrl+D" para deseleccionar..... En Gimp no sé como se hace nada.



Bueno pues resulta que puedes poner los atajos de teclado que tú quieras.
Desde **Editar - Preferencias - Interfaz - Combinaciones de teclas** se puede configurar una por una cada herramienta/acción  que quieras modificar.
Pero eso es un rollo y además, ¿cuando vuelva a instalar el programa? ¿o si quiero usar la misma configuración en otro equipo?
Es mucho más fácil tener un archivo donde se guarden todas esas combinaciones, poder llevarlo a cualquier equipo y que automáticamente Gimp se configure.

Y es lo que os voy a explicar cómo se hace.

Yo lo he probado en Windows 10, si alguien sabe en qué carpeta hay que grabar este archivo en otros Sistemas Operativos lo puede decir en los comentarios del post.

Así pues, en Windows 10, tienes que ir a la carpeta

*C:\Users\ [Tu_nombre_de_usuario] \AppData\Roaming\GIMP\2.10*

Y grabar este archivo
LINK

Y ya está, la próxima vez que abras GIMP, tendrás los mismos atajos de teclado que usas en Photoshop. Incluso puedes editarlo (con el mismo Bloc de Notas) y configurarlo a tu gusto.



Pero es que todavía se pueden hacer muchas más cosas!

En la carpeta *C:\Users\ [Tu_nombre_de_usuario] \AppData\Roaming\GIMP\2.10* puedes:

- gimprc : Ajustes de nuevo documento
  
  - Dimensiones del documento, resolución, espacio de color, etc.

- menurc : Atajos de teclado (acabamos de verlo)

- toolrc : Herramientas de la caja de herramientas
  
  - Puedes modificar el orden de las herramientas dentro de la caja de herramientas

- /brushes : En esta carpeta puedes añadir pinceles, en formato gbr

- /fonts : Carpeta donde se instalan las fuentes

- /plugins : Lo mismo para los plugins

- /splashes : Imagen que aparece en la pantalla de inicio

- /tool-options : Valores por defecto de las herramientas 




