---
title: insert_summary_zoom_frame method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado.

### Devuelve
El [`ISummaryZoomFrame`](/slides/python-net/es/aspose.slides/isummaryzoomframe) recién creado.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará el marco Summary Zoom. |
| x | **float** | La coordenada x del nuevo marco Summary Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Summary Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Summary Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Summary Zoom, en puntos. |

### Observaciones
Este método crea un marco Summary Zoom que agrega enlaces de resumen para todas las secciones de la presentación.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanza si la presentación no contiene secciones, o si la diapositiva objetivo no pertenece a ninguna sección. |

### Ver también
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* clase [`ISummaryZoomFrame`](/slides/python-net/es/aspose.slides/isummaryzoomframe)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)