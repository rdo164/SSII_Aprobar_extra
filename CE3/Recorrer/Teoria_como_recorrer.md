## Array
- Elementos del mismo tipo
### Recorrer un Array 
```
array = [0,2,3,4,5]

for i in array:
    print(i)
```
### Acceder a un elemento específico del Array 
```
array = [0,2,3,4,5]

i = 3
array[i]
```

### Diccionario
- Clave valor
### Recorrer un diccionario
```
dic = {'a': 1, 'b': 2, 'c': 3}

for clave,valor in dic.items():
    print(clave, ", ",valor)
```
### Acceder a un valor específico del diccionario
```
dic = {'a': 1, 'b': 2, 'c': 3}

i = 'b' # 1.seleccionar la clave
dic[i]

```
## Tupla
Es una estructura de datos que almacena una colección ordenada de elementos.

## Recorrer una tupla

```
tup = (100, 200, 300, 400, 500)

for elemento in tup:
    print(elemento)
```

### Acceder a un valor específico de una tupla
```
tup = (100, 200, 300, 400, 500)

i = 3
tup[i]
```
## Resumen del acceso a elementos:

| **Estructura**   | **Forma de acceso**       |
|-------------------|---------------------------|
| **Array**         | `array[indice]`          |
| **Diccionario**   | `diccionario[clave]`     |
| **Tupla**         | `tupla[indice]`          |
