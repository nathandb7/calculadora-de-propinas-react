# Calculadora de Propinas y Consumo

Una aplicación en React y TypeScript que permite calcular propinas y totales de consumo en un restaurante. Los usuarios pueden seleccionar elementos de un menú, elegir un porcentaje de propina, y ver los totales calculados automáticamente.

## Características

- **Menú Interactivo**: Selecciona elementos del menú para agregarlos a la orden.
- **Cálculo de Propina**: Elige entre varios porcentajes de propina predefinidos.
- **Resumen de la Orden**: Ve un resumen detallado de la orden, incluyendo subtotal, propina, y total.
- **Función de Guardado**: Guarda la orden, que reinicia la lista de pedidos.


## Componentes Principales

### App.tsx

Componente principal que contiene la estructura de la aplicación. Incluye:

    * MenuItem: Muestra los elementos del menú.
    * OrderContents: Lista los elementos agregados a la orden.
    * TipPercentageForm: Permite seleccionar el porcentaje de propina.
    * OrderTotals: Muestra los totales de la orden y calcula la propina y el total.

## useOrder.ts

### Custom Hook que maneja el estado de la orden:

    * Funciones: addItem, removeItem, placeOrder.
    * Estados: order (orden actual) y tip (porcentaje de propina).

## OrderContents.tsx

### Muestra la lista de elementos de la orden con:

    * Nombre, precio, y cantidad de cada elemento.
    * Botón para eliminar elementos de la orden.

## OrderTotals.tsx

### Calcula y muestra:

    * Subtotal
    * Propina
    * Total
    * Botón para guardar la orden.

## TipPercentageForm.tsx

 * Formulario que permite seleccionar el porcentaje de propina, mostrando opciones del 10%, 20%, y 50%.

### Se utilizan clases de Tailwind CSS para el diseño de la interfaz.

Licencia
Este proyecto está bajo la Licencia MIT.
