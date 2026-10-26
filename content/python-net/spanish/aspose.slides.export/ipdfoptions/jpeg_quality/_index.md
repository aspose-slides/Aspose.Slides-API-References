---
title: jpeg_quality property
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality propiedad
Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF.
            Lectura/escritura **int**.

### Observaciones

Tiene efecto solo cuando un documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF.
            El valor puede variar de 0 a 100 donde 0 significa la peor calidad pero la máxima compresión y 100 significa la mejor calidad pero la mínima compresión.

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
* clase [`IPdfOptions`](/slides/python-net/es/aspose.slides.export/ipdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)