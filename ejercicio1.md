#ejercicio 1
```python
nombre = str(input("nombre del producto"))
precio = float(input("precio unitario"))
while precio <= 0: 
    precio = print("te equivocaste")
    break
cantidad = int(input("cantidad de productos adquiridos"))
porcentaje = float(input("porcentaje del descuento"))
total = precio * cantidad
descuento = total * (porcentaje / 100)
total_descuento = total-descuento
print (total_descuento)
while 0 >= descuento >= 100:
    print("te equivocaste") 
    break   
while cantidad <= 0:
    print ("te equivocaste")
    break
print(f"{nombre}{precio}{total}{total_descuento}")
```
