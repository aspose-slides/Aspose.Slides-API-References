---
title: add_summary_zoom_frame method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas.

### Devuelve

El [`ISummaryZoomFrame`](/slides/python-net/es/aspose.slides/isummaryzoomframe) recién creado.



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del nuevo marco Summary Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Summary Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Summary Zoom, en puntos. |
| height | **float** | El alto del nuevo marco Summary Zoom, en puntos. |

### Observaciones

Este método crea un nuevo Summary Zoom y coloca una colección de objetos en él para todas las secciones de esta presentación.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si no hay secciones en la presentación, o si la diapositiva de destino no pertenece a ninguna sección. |



### Ver también
* clase [`ISummaryZoomFrame`](/slides/python-net/es/aspose.slides/isummaryzoomframe)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)