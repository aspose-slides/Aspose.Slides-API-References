---
title: insert_section_zoom_frame method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Crea un nuevo marco Section Zoom y lo inserta en la colección de shapes en el índice especificado.

### Devuelve

El recién creado [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar el marco Section Zoom. |
| x | **float** | La coordenada x del nuevo marco Section Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Section Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Section Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Section Zoom, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco Section Zoom;<br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzado si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Crea un nuevo marco Section Zoom con una imagen predefinida y lo inserta en la colección de shapes en el índice especificado.

### Devuelve

El recién creado [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar el marco Section Zoom. |
| x | **float** | La coordenada x del nuevo marco Section Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Section Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Section Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Section Zoom, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco Section Zoom;<br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | La imagen a mostrar dentro del marco Section Zoom. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzado si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |



### Ver también
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISection`](/slides/python-net/es/aspose.slides/isection)
* clase [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)