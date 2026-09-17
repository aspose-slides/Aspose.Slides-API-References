---
title: add_summary_zoom_frame method
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_summary_zoom_frame/
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
| height | **float** | La altura del nuevo marco Summary Zoom, en puntos. |

### Comentarios

Este método crea un marco Summary Zoom que agrega enlaces de resumen para todas las secciones de la presentación.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si no hay secciones en la presentación, o si la diapositiva objetivo no pertenece a ninguna sección. |

### Ver también
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* clase [`ISummaryZoomFrame`](/slides/python-net/es/aspose.slides/isummaryzoomframe)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)