---
title: write_shape_start method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Llamado antes de la renderización de la forma. Llamado una vez por cada forma. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se terminará, el fragmento html añadido se insertará y se iniciará una nueva imagen sobre la anterior.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator) | Objeto de salida. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | Forma que está a punto de renderizarse. |

### Ver también
* clase [`EmbedAllFontsHtmlController`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller)
* clase [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator)
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)