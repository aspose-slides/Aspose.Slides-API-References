---
title: jpeg_quality property
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality propiedad
Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.
            Lectura/escritura **int**.

### Observaciones

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardar en formato PDF.
            El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 significa la mejor calidad pero mínima compresión.

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
* clase [`IHtmlOptions`](/slides/python-net/es/aspose.slides.export/ihtmloptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)