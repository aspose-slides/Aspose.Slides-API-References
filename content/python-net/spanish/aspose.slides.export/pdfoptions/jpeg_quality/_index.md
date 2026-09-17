---
title: jpeg_quality property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality propiedad
Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.
            Lectura/escritura **int**.


### Observaciones

Tiene efecto solo cuando un documento contiene imágenes JPEG.


Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardar en formato PDF.
            El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 significa la mejor calidad pero mínima compresión.


El valor predeterminado es **100** .

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
* clase [`PdfOptions`](/slides/python-net/es/aspose.slides.export/pdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)