# Strategy Pattern

Este Patrón de Diseño es un patrón de comportamiento, organiza el comportamiento que va a tener un objeto. Este comportamiento puede cambiar dinámicamente en tiempo de ejecución.

Este patrón esta compuesto por tres partes:

- Context
- IStrategy
- Strategy

## Context

El Context es la clase de dominio o entidad de donde nosotros vamos a crear el objeto.

## IStrategy

El IStrategy es el contrato que utilizaremos para definir que métodos tienen que ser implementados en sus clases derivadas.

## Strategy

El Strategy es la clase derivada de IStrategy que tendrá su propio comportamiento.



