---
title: from_name method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Crea un color a partir del nombre especificado de un color predefinido.<br/>La búsqueda no distingue entre mayúsculas y minúsculas y ignora los guiones bajos y los espacios: `"LightBlue"`, `"lightblue"` y `"light_blue"` todos se resuelven en `Color.light_blue`. Vea la página de clase [`Color`](/slides/python-net/es/aspose.slides/color) para la lista de colores predefinidos.

### Devuelve

El color nombrado.

```python
@staticmethod
def from_name(name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | **str** | Una cadena que es el nombre de un color predefinido. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **ValueError** | El nombre no es un nombre de un color predefinido. |
| **TypeError** | El nombre no es una cadena. |

### Ver también
* clase [`Color`](/slides/python-net/es/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)