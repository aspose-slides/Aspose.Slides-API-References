---
title: is_visible property
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 130
---
## is_visible propiedad
False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas 
            Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas).
            Solo lectura **bool**.


### Observaciones

Si la etiqueta de datos es visible por defecto, puedes ocultarla por defecto con el método Hide().
            Pero si la etiqueta de datos no es visible por defecto (IsVisible es false) puedes hacer que la etiqueta de datos "visible 
            por defecto" configurando las banderas Show*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat 
            en estado verdadero.

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