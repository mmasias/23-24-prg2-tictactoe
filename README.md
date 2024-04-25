# TicTacToe

## Requisitos

El programa debe permitir a dos usuarios jugar el tres en raya

- Inicialmente el tablero estará vacío
- Los jugadores pondrán las fichas alternativamente, siendo posible alcanzar las "Tres en Raya" con la quinta puesta;
- En caso contrario, una vez puestas las 6 fichas, se moverán las fichas alternativamente;
- Tanto en las puestas como en los movimientos, se deben requerir las coordenadas a usuario validando la corrección de la puesta/movimiento;
- Se debe detectar automáticamente la finalización del juego al lograrse "Tres en Raya": tras la quinta y sexta puesta y tras cada movimiento.

## Desarrollo

### Primera iteración

- [x] Definir la clase: ***TresEnRaya***
- [x] Definir la interfaz: ***jugar()***
- [x] Definir los atributos que hacen falta para realizar la operación de la clase: jugar()
  - [x] Tablero - 1 tablero
  - [x] Jugador - 2 jugadores
  - [x] Turno - 1 turno
- [x]  Codificar los métodos
  - [x] Mostrar el tablero
  - [x] Que al que le toca ponga una ficha
  - [x] Lo anterior se debe repetir hasta que haya tres en raya
  - [x] Pero además hay que cambiar el turno
  - [x] Y validar que luego de colocar tres veces, lo que debe hacer es mover en lugar de poner
  - [x] Si alguien ha ganado, que celebre

> Creamos las clases, métodos y demás que derivan de estas clases (puede ser durante la construcción o al final de la misma).

Recapitulamos, vemos las clases creadas y elegimos una clase para continuar

### Segunda iteración

- [x] Elegir una clase: ***Tablero***
- [x] Definir la interfaz: en este caso, los métodos ya están dados.
- [x] Definir los atributos necesarios para cumplir con los métodos anteriormente indicados (*mostrar, ver si un jugador ya puso todas sus fichas y ver si hay tres en raya*)
  - [x] Almacenaremos las fichas en un array de caracteres.
  - [x] Inicializamos el array en el constructor
- [x] Codificar los métodos
  - [x] Codificamos el método que muestra el tablero: ***mostrar()***
  - [x] Codificamos el método que devuelve si hay tres en raya
    - [x] Apoyándome de un métoro privado que valida si hay tres en raya para un jugador.
  - [x] Codificamos el método que indica si el jugador ya puso todas sus fichas.

Recapitulamos, vemos las clases que quedan pendientes y elegimos la que sigue.

### Tercera iteración

- [x] Elegir la clase: ***Turno***
- [x] Definimos/leemos la interfaz: a quién le toca, a quién no le toca y cambio de turno.
- [x] Definimos los atributos para cumplir con los métodos anteriormente indicados.
  - [x] Almacenaremos el turno en un entero.
- [x] Codificamos el metodo que devuelve a quién le toca: ***toca()***
- [x] Codificamos el metodo que devuelve a quién no le toca: ***noToca()***
- [x] Codificamos el metodo que cambia el turno: ***cambiar()***
