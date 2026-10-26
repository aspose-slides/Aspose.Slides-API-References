---
title: insert_zoom_frame method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe) recién creado.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice base cero en el que insertar el marco Zoom. |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Zoom, en puntos. |
| slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | El [`ISlide`](/slides/python-net/es/aspose.slides/islide) referenciado por el marco Zoom. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si la diapositiva referenciada no pertenece a la presentación actual. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Crea un nuevo marco Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe) recién creado.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice base cero en el que insertar el marco Zoom. |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Zoom, en puntos. |
| slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | El [`ISlide`](/slides/python-net/es/aspose.slides/islide) referenciado por el marco Zoom. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | La imagen para la diapositiva referenciada [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si la diapositiva referenciada no pertenece a la presentación actual. |



### Ver también
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`IZoomFrame`](/slides/python-net/es/aspose.slides/izoomframe)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)