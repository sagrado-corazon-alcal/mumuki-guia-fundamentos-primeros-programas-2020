<a class="sr-only sr-only-focusable" href="../chapters/538-fundamentos/appendix#lectores-de-pantalla">Referencia a la descripción de los tableros para los lectores de pantalla</a>

Para empezar a programar, el primer elemento que vamos a usar es un **tablero** cuadriculado, similar al del Ajedrez, Damas o [Go](http://es.wikipedia.org/wiki/Go).

Estos tableros pueden ser de cualquier tamaño, por ejemplo, 

<table class= "table table-borderless" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">4x4</th>
    <th style="text-align: center">3x2</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board without-header="true">
        GBB/1.0
        size 4 4
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center">
      <gs-board without-header="true">
        GBB/1.0
        size 3 2
        head 0 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>


Siempre vamos a necesitar un tablero sobre el cual **ejecutar** nuestros **programas**, ¡pero despreocupate! nos vamos a encargar de crearlos por vos en cada uno de los ejercicios. Lo interesante es que un mismo programa puede ejecutarse sobre distintos tableros, potencialmente produciendo resultados diferentes. :exploding_head:

> Para confirmar lo que te decimos, presioná el botón Continuar y vamos a generar tu primer tablero: un tablero de 3x3. :grin:

