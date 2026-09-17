---
title: is_visible property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible propiedad
False significa que la etiqueta de datos no es visible de forma predeterminada (y por lo tanto todas las banderas 
            Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas).
            Read-only **bool**.

### Observaciones
Si la etiqueta de datos es visible de forma predeterminada puedes ocultarla de forma predeterminada con el método Hide().
            Pero si la etiqueta de datos no es visible de forma predeterminada (IsVisible es false) puedes hacer que la etiqueta de datos sea "visible 
            de forma predeterminada" configurando las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat
            al estado verdadero.

### Definición:
```python
@property
def is_visible(self):
    ...
```

### Ver también
* clase [`IDataLabelCollection`](/slides/python-net/es/aspose.slides.charts/idatalabelcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)