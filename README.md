# ISR Quincenal

Script para el calculo del ISR Quincenal. Ahorita solo contiene informacion de los años 2020 al 2023. Lo cree con la idea de usarlo en Google Sheets.

Expone una sola funcion llamada `IsrQuincenal` que recibe dos parametros:
- dblIngresoQuincenal
  - Valor numerico del ingreso quincenal (no mensual)
- intPeriodo
  - Año del periodo del ISR (entre 2020 y 2023)

Para usar la funcion en Google Sheets:
- En una hoja de calculo selecciona el menu Extensions -> Apps Script
- Copia el contenido del isrQuincenal.js
- Pega el contenido en el area de codigo de App Script
- Guarda los cambios
- En tu hoja de calculo puedes usarlo como formula de la siguiente manera:
  - `=IsrQuincenal(<Monto Quincenal>, <Año ISR>)`
- Ejemplos
  - `=IsrQuincenal(15323, 2020)`
  - `=IsrQuincenal(A13, B2)`
  - `=IsrQuincenal(A3, $B$3)`
