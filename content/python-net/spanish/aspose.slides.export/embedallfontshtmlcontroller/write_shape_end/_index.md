---
title: write_shape_end method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Se llama antes de la renderización de la forma. Se llama una vez por cada forma. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se terminará, se insertará el fragmento HTML añadido y se iniciará una nueva imagen sobre la anterior.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator) | Objeto de salida. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | Forma que se renderiza al final. |

### Ver también
* clase [`EmbedAllFontsHtmlController`](/slides/python-net/es/aspose.slides.export/embedallfontshtmlcontroller)
* clase [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator)
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)