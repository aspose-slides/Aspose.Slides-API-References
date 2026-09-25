---
title: name property
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/color/name/
weight: 190
---
## name propiedad
Obtiene el nombre de este color.<br/>            Para un color con nombre (una constante con nombre como `Color.red`, o un color creado con [`from_name`](/slides/python-net/es/aspose.slides/color/from_name/)) se devuelve el nombre de .NET, p. ej. `"Red"` o `"LightBlue"`.<br/>            Para cualquier otro color se devuelve el valor ARGB como hexadecimal en minúsculas sin relleno de ceros, p. ej. `"ffff0000"`. `Color.empty.name` es `"0"`.
            Solo lectura **str**.

### Definición:
```python
@property
def name(self):
    ...
```


### Ver también
* clase [`Color`](/slides/python-net/es/aspose.slides/color)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)