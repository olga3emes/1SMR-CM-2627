Sevilla es una ciudad en la que se realizan numerosos conciertos. Cada vez que se organiza uno, hay que tener en cuenta varios aspectos para que salga la actuación como se desea, por lo que se maneja un gran volumen de datos. Por eso se quiere diseñar una base de datos para la gestión de dichos conciertos. Para ello, se tiene información acerca de las salas de conciertos, las orquestas, los compositores y las obras que forman parte del repertorio habitual, así como de los músicos que componen una orquesta y el director.

Cada sala cuenta con un identificador que la distingue de manera unívoca, un nombre, un atributo dirección (formado a su vez por una población, una calle y un número) y un aforo.

Cada obra vendrá identificada por un código, un título y una duración. Además, es necesario conocer su dinámica. Este atributo solo podrá tener los siguientes valores (pianíssimo, piano, mezzo piano, mezzo forte, forte y fortísimo). 

De cada orquesta, se conoce su nombre, nacionalidad y presupuesto. El presupuesto puede venir en números reales.

Se tienen datos personales acerca de los músicos (nombre, DNI, teléfono y fecha nacimiento) y también interesa conocer que instrumentos es capaz de tocar. De cada compositor se guarda su nombre, DNI, fecha y lugar de nacimiento y fecha de fallecimiento. 

Con respecto al director también es necesario guardar información de tipo personal además de guardar sus años de experiencia y las orquestas que dirige. Una persona puede desempeñar cualquiera de estas tres funciones a la vez.

Cuando se celebra un concierto, se conoce el nombre, la fecha y la hora, la sala, la lista de obras y la orquesta que participa, así como el director, el compositor y los componentes de la orquesta. Las fechas se almacenarán en el formato DD/MM/AAAA.

Las restricciones semánticas que se observan son las siguientes:
1) Para cada compositor las obras serán identificadas con un código secuencial (1, 2, 3, …).
2) Un músico puede participar en una sola orquesta.
3) Una obra no se podrá representar los lunes ya que las salas cierran ese día por descanso del personal
