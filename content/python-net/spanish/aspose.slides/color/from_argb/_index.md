---
title: from_argb method
second_title: Referencia de API Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Crea un color a partir de un valor ARGB de 32 bits.

### Devuelve
El color creado a partir del valor especificado.



```python
@staticmethod
def from_argb(argb):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | **int** | Un valor que especifica el valor ARGB de 32 bits (con signo o sin signo). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | Un valor de componente es menor que 0 o mayor que 255. |
| **TypeError** | Número o tipo de argumentos incorrecto. |


## from_argb(alpha, base_color) {#int-color}
Crea un color a partir del valor alfa especificado y del color base.

### Devuelve
El color creado a partir de los valores especificados.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alpha | **int** | El valor del componente alfa. Los valores válidos son de 0 a 255. |
| base_color | [`Color`](/slides/python-net/es/aspose.slides/color) | El color a partir del cual crear el nuevo color. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | Un valor de componente es menor que 0 o mayor que 255. |
| **TypeError** | Número o tipo de argumentos incorrecto. |


## from_argb(red, green, blue) {#int-int-int}
Crea un color opaco (alpha es 255) a partir de los valores rojo, verde y azul especificados.

### Devuelve
El color creado a partir de los valores especificados.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| red | **int** | El valor del componente rojo. Los valores válidos son de 0 a 255. |
| green | **int** | El valor del componente verde. Los valores válidos son de 0 a 255. |
| blue | **int** | El valor del componente azul. Los valores válidos son de 0 a 255. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | Un valor de componente es menor que 0 o mayor que 255. |
| **TypeError** | Número o tipo de argumentos incorrecto. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Crea un color a partir de los cuatro valores de componentes ARGB (alpha, rojo, verde y azul).

### Devuelve
El color creado a partir de los valores especificados.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alpha | **int** | El valor del componente alfa. Los valores válidos son de 0 a 255. |
| red | **int** | El valor del componente rojo. Los valores válidos son de 0 a 255. |
| green | **int** | El valor del componente verde. Los valores válidos son de 0 a 255. |
| blue | **int** | El valor del componente azul. Los valores válidos son de 0 a 255. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | Un valor de componente es menor que 0 o mayor que 255. |
| **TypeError** | Número o tipo de argumentos incorrecto. |



### Ver también
* clase [`Color`](/slides/python-net/es/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)