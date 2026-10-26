---
title: from_known_color method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Crea un color a partir del color predefinido especificado.<br/>Esta es la única forma de obtener un color del sistema (como `KnownColor.CONTROL`): los colores del sistema no se exponen como atributos de `Color` porque sus valores dependen del tema del escritorio, por lo que se leen del tiempo de ejecución de la biblioteca.

### Devuelve

El color que crea este método.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| known_color | **KnownColor** | Un elemento de la enumeración `KnownColor` (un `IntEnum` que refleja .NET `System.Drawing.KnownColor`) o su valor entero. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | El valor no es un miembro válido de `KnownColor`. |



### Véase también
* clase [`Color`](/slides/python-net/es/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)