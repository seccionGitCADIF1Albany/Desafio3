TAREA 3
1.- Haga un programa nuevo en psint, declare las variables necesarias con el tipo de datos más apropiado
2.- Escriba las instrucciones necesarias para leer las entradas (el precio del cartón de huevos y el número N de huevos detallados que desea comprar)
3.- Haga el cálculo para determinar cuál es el precio de un huevo cuando se compra detallado (use asignaciones)
4.- Haga el cálculo para determinar cuál es monto que debe pagar alguien por la compra de N huevos detallados
5.- Muestre las salidas del precio del huevo detallado y el monto que debe pagar al comprar N huevos detallados

Definir deta como entero
Definir pre,total,hue,monto como real
Mostrar “Ingrese precio del cartón de huevos:”
Leer pre   
Mostrar “Ingrese cantidad de huevos detallados:”
Leer deta   
total=pre/36
Hue=(total*0.2)+total
Mostrar “El precio del huevo detallado es:”, hue
Monto=hue*deta
Mostrar “El monto total a pagar es:”, monto
