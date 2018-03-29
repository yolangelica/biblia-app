# Bibliapp

Con esta aplicación el usuario logrará tener inspiración o solamente disfrutar de su lectura biblica en cualquier momento del día, mientras viaja, durante los cultos o si necesita compartirlo con alguien.Siempre estará disponible el versículo que necesite a sólo un par de click, además de lograr guardar o marcar el capitulo o versiculo que necesite.

![biblia-logo](https://user-images.githubusercontent.com/32304271/38070591-1edaa7a4-32f3-11e8-97c9-5202b50ff90f.png)

Ahora tendrá a su disposición y a todas horas la palabra que necesite, sin tener peso extra en su bolso.
- Interfaz amigable al usuario y de rápido acceso a los libros, búsqueda simple.
- Disfruta de contenidos con reflexiones poderosas acerca de las escrituras a través de la búsqueda de versículos. 
- Guarde sus versículos con marcadores y retome sus lecturas más tarde.

Desarrollado para: [Laboratoria](http://www.laboratoria.la/)

## PROCESO

Se plantea el siguiente reto: 
Re-diseñar e impleméntar una versión mejorada de la Biblia, en 36 horas.
Equipo: 3 Front-end + 1 Ux (Yolanda Rayman).

a continuación describiré el proceso Ux que guié para llegar al prototipo.

Se utilizó la modalidad ágil para  para trabajar colaborativamente en equipo y obtener el mejor resultado posible ante la limitación de tiempo.(36 horas)

Se realiza una planificación que consta de:

- Investigación: Benchmark, revisión de comentarios de la app, test usabilidad.
- Síntesis/definición: identificación problemáticas comunes.
- Ideación: revisión de contenidos, realización de sketch y propuestas de forma individual.
- Testeo: se testea, en razón del tiempo, con usuarios presentes en el mismo lugar, luego se valida con 2 usuarios cristianos.
- Se distribuyen tareas para la realización del producto en el equipo.

## INVESTIGACIÓN

- Se elige una de las biblias más descargadas.
- Investigación sobre tipos de biblias, según religión.
- Investigación sobre contenido de biblia, su distribución, lenguaje de usuarios según religión.


Para descubrir la  problemática, se buscan los puntos de dolor del usuario, mediante la lectura de los comentarios que aparecen en las descargas, así también se valida que tan utilizada es esta app y en qué momentos la utilizan.

![](https://github.com/yolangelica/biblia-app/blob/master/img/coment.png)
![](https://github.com/yolangelica/biblia-app/blob/master/img/comet2.png)

Luego de descargar y revisar la app, se testea  con las mismas integrantes del equipo, sólo para optimizar el tiempo.
Se les entrega un contexto: “Tienes tu biblia descargada en tu celular y necesitas, ahora que estás en tu tiempo de descanso, inspiración para continuar con tus tareas” se le dan tareas y se graba el proceso.
las tareas solicitadas:

1 Busca el libro Génesis, capítulo 1, versículo 16.
2 Guarda éste versículo.
3 Revisa los versículos guardados.
4 Elimina el versículo.
5 Cambia el tamaño del texto, hazlo más grande y vuelve a tu lectura Génesis.

**Resultados:**

- Todas van al buscador primero, pero este no arroja ningún resultado.
- El título “TABLA DE CONTENIDO” no se relaciona inmediatamente con los libros bíblicos y sus capítulos.Se valida si es confuso este título más adelante, testeando a 2 personas cristianas, quienes sugieren el título de “Libros” o simplemente “Biblia” como aparece en sus aplicaciones personales. 
- En cuanto a los versículos, pueden guardar sólo capítulos, pero parece confuso ya que al apretar la etiqueta, además aparece un texto que tiene la función de guardar o borrar, muy cercanos.
estos versículos al revisarlos no se pueden eliminar inmediatamente, solo borrar el texto a través del teclado letra a letra.
- Tamaño texto: para modificar texto, todos acceden sin dificultad, este problema aparece al momento de dar el máximo de tamaño y la pantalla se desplaza para el lado, realizando el movimiento de cambio de pantalla, no permite el máximo de texto de forma simple e inmediata.
 
 
## SÍNTESIS

Para la síntesis utilicé post it, separé a los usuarios testeados y bajo su nombre  identifiqué cada dificultad que tuvieron en el test de usabilidad de la app, luego con stickers de colores, se identificaron con un color en común cada problemática similar.
Ejemplo:
Problemas con el buscador= color verde.
Problemas con el tamaño texto= color azul.

![](https://github.com/yolangelica/biblia-app/blob/master/img/test.jpg)
![](https://github.com/yolangelica/biblia-app/blob/master/img/test2.jpg)


**Resumen Investigación:** La app parecía simple, sin embargo las dificultades aparecen en el buscador que no entrega resultados, o también en las  etiquetas del menú, o la búsqueda de versículos en varios pasos, lo dificultan.



### Producto Mínimo viable
Por esto elegimos desarrollar la mejora en la búsqueda simple de versículos, en menos pasos, mejorando la etiqueta “tabla de contenidos” por “biblia”.

![](https://github.com/yolangelica/biblia-app/blob/master/img/menu.png)


 
## IDEACIÓN

Se realiza mapa de contenidos y posible flujo para lograr el objetivo, (basados en la app a mejorar).

![](https://github.com/yolangelica/biblia-app/blob/master/img/1.jpg)
![](https://github.com/yolangelica/biblia-app/blob/master/img/arq.jpg)


 Se les presenta al equipo el mapa de contenido y se les explica la distribución, con este conocimiento entregado, se le entrega una hoja a cada integrante y se les pide crear sketch rápidos con posibles soluciones, (siguiendo metodología Scrum) en 15 minutos.
Luego cada una explica su sketch, si siente que faltó algo o no quedó clara una idea se pega un post-it con esta información y finalmente se entregan 3 stickers a cada una para votar por las soluciones que les parecen mejores.
Estos son los resultados del proceso

![](https://github.com/yolangelica/biblia-app/blob/master/img/sketch.jpg)

Se crea el siguiente Sketch
Se mejora el Sketch para testear

![](https://github.com/yolangelica/biblia-app/blob/master/img/sket.jpg)
![](https://github.com/yolangelica/biblia-app/blob/master/img/skett.jpg)

El que tendrá función sólo en la busqueda por versículos.

Para finalizar, luego de tener definidas las pantallas y sus correcciones se organiza el equipo Front-end y Ux en:
-Por hacer, En Proceso,Finalizado.
Para ver el avance de cada tarea, se realizan retrospectivas cada 2 horas.

##### Tareas Principales:

- Buscar Api Biblia y utilizarla (massiel y Vanessa )día 1-2
- Investigar React y crear componentes (Vanessa-Mariajosé) día 1-2
- Firebase (Vanessa) día 2
- Crear Readme registrando proceso(Yolanda)día 2
 

 **Dificultades en el proceso**
 - Problemas al encontrar API
 - Api utilizada está en Inglés.
 - Breve tiempo de entrega.
 - Por Limitación de tiempo  se cambia wireframe, en pantalla de busqueda de versiculos.


 **Solución**
- 2 personas del equipo buscan API
- Se utilizará api en inglés, pensando en lograr cambiar idioma más adelante.
- Distribución de trabajo
- Se propone nueva pantalla de busqueda a Front-end que puedan llevar a cabo en el tiempo estipulado, se crea 2°prototipo.

Se presenta el segundo prototipo finalizadas las 36 horas de Hackaton Laboratoria.

 
 ## PROTOTIPADO

- Herramienta: marvelapp

Link 
Prototipo1 : en marvelapp: https://marvelapp.com/863ihje
Prototipo 2: Se propone por Front modificar la busqueda, según API, se crea prototipo2:https://marvelapp.com/326j7i5

## Conclusión

Según lo descubierto se identifican distintas opciones para mejorar en la aplicación Biblia reina valera 1960, nos enfocamos en la búsqueda simplificada de textos bíblicos , reduciendo 3 pasos en sólo una pantalla.
Se acuerda con el equipo front-end, el que está involucrado en todo el proceso, sobre el mínimo viable que pueden llevar a cabo en el tiempo propuesto y a partir de esto se crean sketch en conjunto con el equipo, se testean y realizan 2 prototipos, el primero es desechado ya que el equipo no cree lograr alcanzar este resultado y el segundo se propone según lo que indica el equipo, no perdiendo el foco en el objetivo y necesidades del usuario.
Es importante siempre trabajar en conjunto, mantener la comunicación y honestidad sobre las capacidades y limitaciones para buscar soluciones rápidas ante eventualidades que puedan surgir en el camino, también estar atenta a su desarrollo, no abandonando como Ux la realización del proceso, para dar solución a estas problemáticas que puedan aparecer en el momento indicado.


