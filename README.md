# taller_2_godot
# Descripción del juego y proceso de desarrollo
#264090-Santiago Morales

El juego consiste en un escenario donde el jugador controla a un personaje llamado *PurpleWarrior*, el cual puede moverse y atacar utilizando una hitbox para eliminar enemigos. Dentro del nivel se encuentran varios enemigos llamados *RedLancer*, los cuales interactúan con el jugador mediante un sistema de combate básico donde reciben daño y pueden ser eliminados.

Adicionalmente, se implementó un enemigo especial tipo jefe (*RedLancerBoss*), el cual introduce una mecánica más avanzada. Este enemigo permanece inactivo al inicio y solo se activa cuando los otros enemigos han sido derrotados. Una vez activado, el boss persigue al jugador, posee mayor cantidad de vida y realiza ataques más fuertes con un tiempo de recarga, lo que lo convierte en un desafío más complejo dentro del juego.

## Proceso de desarrollo

Para el desarrollo del proyecto, primero se siguió el tutorial base proporcionado por el profesor, donde se implementó el personaje principal con movimiento, animaciones y sistema de ataque.

Posteriormente, se creó una clase base llamada *Character*, la cual contiene atributos y métodos comunes como la vida, la recepción de daño y la muerte. Esta clase permitió aplicar el concepto de herencia, haciendo que tanto el héroe como los enemigos compartieran una misma estructura base.

Luego, se adaptaron los enemigos existentes para que heredaran de esta clase base, modificando su comportamiento para que utilizaran un sistema de daño en lugar de eliminarse directamente.

Finalmente, se añadió un tercer enemigo tipo boss con lógica adicional, utilizando condiciones y temporizadores para controlar su activación y sus ataques.

## Conclusión

El proyecto integra conceptos fundamentales de programación orientada a objetos como la herencia y la reutilización de código, junto con mecánicas básicas de videojuegos como el movimiento, el combate y la interacción entre entidades dentro de un mismo escenario.
