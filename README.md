# Ejercicios con forumularios y Vue


Abre con Live Server cada uno de los ficheros index.html del ejercicio a ralizar

## ¿Algo va mal?


0. Intenta no pedir la solución directa a la IA.
1. Asegurate de que has hecho bien el [setup]((https://vuejs.org/guide/quick-start.html#using-the-global-build)) , engoblado todo el HTML por un contenedor `<div id="app"></div>` 
2. Echa un vistazo a la consola del navegador. Normalmente sucede que nos olvidamos importar algo o hay un error de sintaxis
<img src="https://oscarm.tinytake.com/media/17910d3?filename=1753086794204_TinyTake21-07-2025-10-33-00_638886835924646084.png&sub_type=thumbnail_preview&type=attachment&width=615&height=486" title="Powered by TinyTake Screen Capture"/>

# 0-renfe-travels

Usa adecuadamente la directiva [v-for](https://vuejs.org/guide/essentials/list.html#v-for) en el <li> , para generar tantos <li> como viajes hay en la variable de estado _trips_ (ignora por favor el uso de `<br>` para maquetar 🫠)

Solaente hay que modificar adecuadamente el HTML con la directiva v-for para que funcione.

# 1-dice-roll

Este ejercicio está implementado a medias

1. Completa adcuadamente el método _roll_ para que, cada vez que hacemos clic en "Roll Dice", la variable de estad _dice_ pase a ser un número aleatório de 1 a 6
2. Usa adecaudamente la dierctiva v-for para mostrar una lista con el historial de tiradas
3. Haz funcionar el botón _Clear history_ para que al pulsarlo se limpie por completo el historial

# 2-counter-color

En este ejercicio queremos cambiar el color del contador en función de su valor:

1. Si es 0 o negativo, cambiaremos el color a rojo
2. Si es un número positivo, cambiaremos el color a verde

Hay varias formas de conseguir esto. Tan solo tienes que modificar la **línea 20** del HTML para conseguirlo. 

1. Usa adecuamente [estilos en línea dinámicos](https://vuejs.org/guide/essentials/class-and-style.html#binding-to-objects-1) pa

2. Fíjate en las clases CSS .red y .green que hay en el fichero **styles.css**. Otra forma de consegujirlo es unsar clases CSS dinámicas - [ejemplos](https://www.w3schools.com/vue/vue_css-binding.php). Otros [ejemplos de w3school](https://www.w3schools.com/vue/vue_css-binding.php) . ¡Incluso podrías usar una [clase CSS de Boostrap](https://getbootstrap.com/docs/5.0/utilities/colors/#colors)!


# 3-random-color-generator

Cada vez que pulsamos el botón de generar color aleatorio, se debe añadir un nuevo contenedor con el número del color aleatório.

1. Primero haz que simplemente aparezca el número en medio de la caja
2. Luego, averigua como usar estilos en línea en Vue3 para que, cada elemento, sea el color de fondo del número generado.

# (Opcional) 999-tutti-frutti

Pon en práctica tus conocimientos de Vue para generar un comportamiento parecido a la app al esperado en el vídeo