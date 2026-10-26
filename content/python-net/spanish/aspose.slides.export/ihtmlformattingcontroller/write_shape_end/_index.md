---
title: write_shape_end method
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Se llama antes de la renderización de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento HTML añadido y se iniciará una nueva imagen encima de la anterior.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator) | Objeto de salida. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | Forma que se renderiza al final. |


### Ver también
* clase [`IHtmlFormattingController`](/slides/python-net/es/aspose.slides.export/ihtmlformattingcontroller)
* clase [`IHtmlGenerator`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator)
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)