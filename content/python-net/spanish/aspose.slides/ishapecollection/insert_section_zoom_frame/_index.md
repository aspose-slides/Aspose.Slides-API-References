---
title: insert_section_zoom_frame method
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Crea un nuevo marco de zoom de sección y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe) recién creado.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice base cero en el que se inserta el marco de zoom de sección. |
| x | **float** | La coordenada x del nuevo marco de zoom de sección, en puntos. |
| y | **float** | La coordenada y del nuevo marco de zoom de sección, en puntos. |
| width | **float** | El ancho del nuevo marco de zoom de sección, en puntos. |
| height | **float** | La altura del nuevo marco de zoom de sección, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco de zoom de sección;<br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Crea un nuevo marco de zoom de sección con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe) recién creado.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice base cero en el que se inserta el marco de zoom de sección. |
| x | **float** | La coordenada x del nuevo marco de zoom de sección, en puntos. |
| y | **float** | La coordenada y del nuevo marco de zoom de sección, en puntos. |
| width | **float** | El ancho del nuevo marco de zoom de sección, en puntos. |
| height | **float** | La altura del nuevo marco de zoom de sección, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco de zoom de sección;<br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | La imagen a mostrar dentro del marco de zoom de sección. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |



### Ver también
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISection`](/slides/python-net/es/aspose.slides/isection)
* clase [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)