---
title: best_images_compression_ratio property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio propiedad
Indica si la compresión más efectiva (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que conducirá a un tamaño menor del documento PDF resultante. La selección de la mejor relación de compresión de imágenes es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es **bool**.false por defecto.

### Observaciones

El valor predeterminado es **bool**.false.

### Definición:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### Ver también
* clase [`PdfOptions`](/slides/python-net/es/aspose.slides.export/pdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)