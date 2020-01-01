# Notas de JAVASCRIPT - AJAX
## Estado del objeto XMLHttpRequest() (Ciclo de vida)

La propiedad que muestra el estado del objeto es `readyState`$\in[0,4]$
*   0: Todavía no se llamó `open()`
*   1: Todavía no se llamó `send()`
*   2: `send()` ya fue invocado, y los cabezados y el estado ya están disponibles.
*   3: Descargando; `responseText`contiene información parcial.
*   4: La operación está terminada.

<u>INVESTIGAR: <b>Técnica AHAH</b></u>

## Procesar datos tipos JSON
