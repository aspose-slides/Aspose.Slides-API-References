---
title: write_shape_start method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Llamado antes de la renderización de shape. Llamado una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se completará, se insertará el fragmento html añadido y se iniciará una nueva imagen encima de la anterior.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator) | Objeto de salida. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | Shape que está a punto de renderizarse. |

### Véase también
* clase [`IHtmlFormattingController`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller)
* clase [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator)
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)