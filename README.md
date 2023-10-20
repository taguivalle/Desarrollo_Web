# Desarrollo_Web

Par poder realizar este tipo de proyectos "Desarrollo Web Completo con HTML5, CSS3, JS, AJAX, PHP y MySQL" se tuvo en cuenta diferentes formas de desarrollo que se van presentando uno
tras otro con el objetivo principal de que sea más fácil de entender este. así mismo se presentan una serie de pasos por
cada función de desarrollo.

Los 4 proyectos principales de este curso los puedo resumir de la siguiente manera:
Primero: Proyecto inicial una especie de DevWebCamp o una conferencia.

INTRODUCCIÓN AL PROYECTO FINAL.
Inicialmente, este tendrá un registro para que el usuario pueda ingresar los datos respectivos como es normal en todo tipo de plataformas que exigen ingresar unos datos específicos para poder interactuar con nuestra página; o sí ya se tiene una cuenta se podrá iniciar sesión desde la opción iniciar sesión.

Seguidamente, en la parte intermedia de la página se encuentra una barra de navegación para que realice la opción correspondiente de cada ventana entre eventos, paquetes, workshops, conferencias comprar pasaje y por ende cada ventana u opción tendrá su propia descripción. Ahora sí nos dirigimos un poco más hacia abajo observaremos un slider, que nos permitirá tener una gama de opciones de eventos.

De otra parte, estos registros que se tienen se encuentran alojados en una BASE DE DATOS, y lo que hace un poco más complejo toda esta parte es que vamos a tener dos tipos de eventos, tenemos conferencias y como se mencionó en el anterior artículo tenemos un workshops, tenemos dos días; los viernes y los sábados. con base en esto estaremos viendo un poco más adelante el demo del admin para mostrar como funciona esta parte; par qué no se repitan horas.

También, se tiene la opción y una vez que el usuario realice su pago, va a poder elegir hasta cinco conferencias; alternadamente, estaremos viendo la parte de la disponibilidad, debido a que le fijaremos un número a cada evento, por decir algo el número 30; y una vez que se encuentren en ceros, ya no se puede registrar más usuarios. es decir se muestra como sería algo como un contador de eventos.

Posteriormente, estaremos viendo como crear animaciones, como integrar una librería de animaciones que al momento de hacer un scroll se realiza lo correspondiente de las animaciones. También, se tienen los speakers; siendo estos que al momento de que las personas que van a impartir tanto conferencias como workshops y se observará que van apareciendo estas animaciones de los speakers y de inmediato se observa que se tiene por ejemplo, diferentes backgrounds en cada animación de los speakers.

Además, se tiene la información primaria por así decirlo de cada conferencista con la procedencia del país, sus redes sociales con sus respectivas habilidades. siguiendo con un poco de scroll tenemos un mapa que sirve de orientación de dónde se llevará el evento. finalmente se tienen los boletos de entrada de la conferencia. A través de estos se tiene la posibilidad de elegir tres (3) planes presenciales y que se debe de consignar un valor de $199, el virtual que tiene un valor de &49 y uno gratis que es totalmente en ceros pesos. Es natural que, para esta clase de páginas se tenga un footer; y este contiene un menú de redes sociales.

Como se mencionó anteriormente, se tiene un inicio de sesión para este primer paso vamos a iniciar como administrador, ingresando las credenciales propia para este rol; se observará que nos lleva al panel propiamente dicho al panel de adminsitración. también vamos a tener una ventana de ponentes al lado izquierdo de la página de administración en donde se puede registrar nuevos ponentes o conferencistas.

Sí al momento de interactuar con la ventana de administración se presiona en un nuevo ponente, esta acción nos lleva a un formulario de registro de datos de información personal del nuevo ponente que lo tienen la mayoría de los formularios en la web; pero lo novedoso es que se tiene la opción de agregar el área de experiencia y al momento de guardar aparece un tags que se van asociando al ponente y sí abrimos la página principal, eso es lo que aparece en la parte inferior de cada ponente.

Otro aspecto fundamental, es que esta clase de tags la manejaremos con JavScript y al abrir esos tags en nuestro código se observa que lo realiza un keyCode quien es el que hace la magía; permitiendo a su vez de validar para que este requisito de experiencia no valla a ser vacío. También vamos a tener las redes sociales con su FaceBook, Twitter, Youtube o cualquier red social que tenga el ponente o usuario. Esto iconos los traemos de fonts awesome y vemos como generar este tipo de inputs con puro código de HTML y CSS. también se tiene la manera de eliminar, editar y también añadirlo.

Notemos que, en la parte derecha se tiene una paginación para mostrar la opción de cuál página se está interactuando y cuantas más quedan por recorrer, por decir la secuencia. permitiendo mostrar un siguiente sí se coparon todas las páginas y poder regresarnos con una acción anterior o a un página anterior. Esta paginación es de tipo Google y que se hizo a manera de estructura de ellos. es decir mediante cuantos registros por página quiere que se vea dentro de esta; así mismo se va alimentando la paginación.

Probablemente, para algunos se muestra la sección de pagos de este evento, algunos son conferencia y otros workshops siendo este el objetivo principal de esta página; mostrando los días viernes y sábado; ahora, al presionar añadir evento y supongamos que vamos a crear un evento, por ejemplo de PHP 8, qué es lo más nuevo, se tiene un cajon de descripciones para decirle al usuario que lo que van a aprender y depués viene la categoría o tipo de evento permitiendo seleccionar de un desplegable workshops y conferencias.

Notése, que las horas inicialmente están deshabillitadas porque requerimos la categoría del evento y el día de realizarse este; de esta forma vamos a ver que horas se encuentran disponibles, sí se selecciona sábado por ejemplo y después se observa que se encuentra deshabilitado porque esa hora ya está seleccionada para otro evento. Ahora nos dirigimos a eventos, conferencias en el día sábado, puede observarse que existe una conferencia para ese día y con esto podemos evitar que se encuentren registros duplicados.

Análogamente, se tiene la posibilidad de escoger la hora y el día dependiendo de la disponibilidad para que el usuario decida lo pertinente, ahora suponiendo que se cuenta con cincuenta (50) cillas o lugares, por lo tanto nos podemos registrar a este evento, entonces, se puede registrar a este evento.

Cuando se hace un registro exitoso se tiene una validación por medio de un correo electrónico, para este caso se usó mailtrab como medio de validación y se obtiene los respectivos datos de registro de la cuenta y que se debe de validar o confirmar dicha cuenta. Y sí regresamos a la página debe de aparecer la respectiva validación del correo registrado.

Como es obvio, se inicia la sesión con el usuario registrado anteriormente y este debe de elegir un plan presionando en inscripción bién sea gratis ya genera un boleto virtual y confirma mediante un mensaje que ya se encuentra inscrito a la webcam; ahora, los otros dos planes presencial y virtual se tiene que cancelar con los valores que se manifestaron anteriormente.

Nuevamente, se tiene la opción en los planes de pago realizarlo por PayPal, tarjeta de crédito y/o débito; presionando en el botón de pagos expandiendo el respectivo formulario en donde se deben de ingresar los respectivos datos como es de costumbre en este tipo de transacciones. Como lo argumenté se tiene la opción de cancelar el pago por PayPal y al presionar directamente sobre este y lo normal nos pide iniciar sesión del registro en PayPal; es lógico que para esta actividad académica no ingresaremos dinero real; pero es la simulación exacta de lo que se hace con la plataforma PayPal.

Se podrá observar que, nos lleva hacia nuestra página y es aquí en donde se puede elegir hasta cinco eventos para asistir de forma presencial; y se tiene la opción de seleccionar un regalo, por ejemplo un paquete de stickers o una camiseta del evento y para el tipo de persona que desee obtener, o sea sí es hombre o mujer. Con sus respectivas validaciones y de inmediato ya el usuario puede empezar a ingresar las conferencias que sean de su interés, permitiendo seleccionar los cinco eventos y no podrá seleccionar unos más.

Otro aspecto a tener en cuenta es el manejo de la base de datos que nos permitirá ver reflejado el dinero virtual de los pagos realizados para el evento DewebCam y que ha sido ingresado a la cuenta de PayPal, es importante este punto debido a que da una exactitud del dinero ingresado a la cuenta del organizador del evento y además de las comisiones que cobra la plataforma PayPal.

RESUMEN:
Esta página puede ser muy útil, llegado el caso sí se quiere crear un sistema para un doctor y agendar sus citas y/o sí se quiere elaborar el calendario de vacaciones para empresa donde labores en la intranet, también, se puede aprovechar de esta clase de página y el código se puede impolementar en diferentes escenarios. Es muy común hoy en día ver este tipo de proyectos, incluso sí se quiere crear un CLON de Airbn va a ser de gran utilidad este código. Se observa que, esta página tiene una funcionalidad muy precisa para que no tenga margén de errores.

INTRODUCCIÓN AL PROYECTO Desarrollo Web Completo con HTML5, CSS3, JS, AJAX, PHP y MySQL.

Inicialmente, este proyecto ya es el primero que incluye el lenguaje de programación en el Backend estaremos haciendo PHP en donde almacenamos y mostramos información de una base de datos. Entonces este proyecto ya va a ser un poco más complejo; debido a que estaremos creando un proyecto para un negocio de bienes raices, en donde se va a poder anunciar sus propiedades que tienen ne venta.

En cuanto a la arquitectura que utilizaremos para elaborar este proyecto, estaremos creando un framework MVC (Model view Controller) de igual manera, estaremos creando todo el código, no utiliza un framework, nosotros mismos lo hacemos; algo importante es que este proyecto pasa primero de funciones o código spaguetti, como se le dice normalmente, después implementamos programación orientada a objetos y después lo llevamos ya a un framework propio; MVC.

Vamos a tener una carpeta SRC como vamos a encontrar en muchos frameworks hoy en día, por ejemplo, No JS, laravel mismo o también de react. además tenemos una separación muy importante aquí en el cual tenemos controladores, tenemos modelos y tambien vistas que es la principal del framework MVC. Todo esto lo estaremos haciendo nosotros mismos. devido a que no utiliza un framework, no utiliza laravel, no utiliza WordPress que no tiene nada que ver con este tema, es código hecho por nosotros mismos.

También, vamos a tener una zona privada como pública con sus respectivas autenticaciones; OJO QUEDAMOS EN EL MINUTO TREINTA Y SEIS.
