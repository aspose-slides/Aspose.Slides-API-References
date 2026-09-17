---
title: jpeg_quality property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality propiedad
Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.
            Lectura/escritura **int**.


### Observaciones

Sólo tiene efecto cuando un documento contiene imágenes JPEG.


Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF.
            El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero la máxima compresión y 100 significa la mejor calidad pero la mínima compresión.


El valor predeterminado es **95** .

### Definición:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Ver también
* clase [`HtmlOptions`](/slides/python-net/es/aspose.slides.export/htmloptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)