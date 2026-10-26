---
title: add_zoom_frame method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Crea un nuevo marco Zoom y lo agrega al final de la colección de formas.

### Devuelve

El [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe) recién creado.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Zoom, en puntos. |
| slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | El [`ISlide`](/slides/python-net/es/aspose.slides/islide) referenciado por el marco Zoom;<br/><br/>            debe pertenecer a esta presentación. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada si la diapositiva referenciada no pertenece a la presentación actual. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Crea un nuevo marco Zoom y lo agrega al final de la colección de formas.

### Devuelve

El [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe) recién creado.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Zoom, en puntos. |
| slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | El [`ISlide`](/slides/python-net/es/aspose.slides/islide) referenciado por el marco Zoom;<br/><br/>            debe pertenecer a esta presentación. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | La imagen para la diapositiva referenciada [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada si la diapositiva referenciada no pertenece a la presentación actual. |



### Ver también
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)