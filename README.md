# -GDV-IB-Aguin_Garcia_Paula---Entrega-4-Videojuego-Monta-un-PC-
Descripción

Este proyecto es un videojuego educativo creado en Construct 3 para la asignatura de Informática Básica. El objetivo del juego es que el jugador aprenda a identificar y colocar correctamente los componentes principales de un ordenador dentro de una torre ATX.

El juego incluye:

Menú de bienvenida con botón para iniciar la partida.

Mecánica de arrastrar y soltar componentes.

Preguntas con entrada de texto: el jugador debe escribir el nombre correcto del componente para desbloquearlo.

Colocación de los componentes en la torre mediante objetos invisibles y comportamiento “Pegado”.

Sistema de puntuación que aumenta cada vez que el jugador acierta.

Menú final con mensaje de victoria y botón para reiniciar el juego.

Componentes del ordenador utilizados

Caja ATX (torre del ordenador)

Placa base

Procesador (CPU)

Disipador de CPU (ventilador o cooler)

Memoria RAM

Tarjeta gráfica

Fuente de alimentación (PSU)

Mecánicas principales

Importar sprites de los componentes y añadir referencia al ratón para poder interactuar.

Asignar comportamiento Arrastrar y soltar a los objetos, inicialmente deshabilitado.

Añadir comportamiento Pegado para que los componentes se fijen a la torre.

Crear entradas de texto para que el jugador escriba el nombre del componente.

Programar la condición:

Si el texto introducido coincide con el nombre correcto → habilitar arrastrar y soltar.

Colocar objetos invisibles en la torre como puntos de referencia.

Cuando el componente se superpone al objeto invisible → se pega a la torre.

Crear una variable global de puntuación.

Cada acierto suma +1.

Se muestra en pantalla mediante un objeto de texto.

Al colocar todos los componentes correctamente → aparece mensaje de victoria y menú final.

Objetivos educativos

Aprender los nombres y funciones de los componentes básicos de hardware.

Relacionar teoría de Informática Básica con práctica interactiva.

Desarrollar habilidades de lógica y asociación mediante mecánicas de juego.

Cómo jugar

Escribe el nombre correcto del componente en la caja de texto.

Si aciertas, podrás arrastrar y soltar el componente.

Colócalo en el lugar correcto de la torre.

Repite hasta completar los 7 componentes.

¡Gana la partida cuando todos estén colocados correctamente!

Créditos

Autor: Apellido1 Apellido2 Nombre

Asignatura: Informática Básica – Práctica 4

Grado: Diseño de Videojuegos

Universidad: Universidad de Burgos

Curso académico: 2025–2026

Herramienta: Construct 3

Control de versiones: GitHub Desktop

Licencia

Este proyecto está bajo la licencia Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC-BY-NC-SA-4.0). Esto significa que puedes compartir y adaptar el contenido solo para fines no comerciales, siempre que se dé crédito al autor original y las obras derivadas se distribuyan con la misma licencia.
