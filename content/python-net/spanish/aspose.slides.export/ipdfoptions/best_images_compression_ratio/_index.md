---
title: best_images_compression_ratio property
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio propiedad
Indica si se debe seleccionar automáticamente la compresión más eficaz (en lugar de la predeterminada) para cada imagen. Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un tamaño menor del documento PDF resultante. La selección de la mejor relación de compresión de imágenes es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es **bool**.false por defecto.

### Observaciones

Por defecto es **bool**.false.

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
* clase [`IPdfOptions`](/slides/python-net/es/aspose.slides.export/ipdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)