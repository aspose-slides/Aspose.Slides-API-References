---
title: add_section_zoom_frame method
second_title: Referencia de la API Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Crea un nuevo marco Section Zoom y lo agrega al final de la colección de formas.

### Devuelve

El [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe) recién creado.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del nuevo marco Section Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Section Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Section Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Section Zoom, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco Section Zoom; <br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Crea un nuevo marco Section Zoom con una imagen predefinida y lo agrega al final de la
            colección de formas.

### Devuelve

El [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe) recién creado.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del nuevo marco Section Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Section Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Section Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Section Zoom, en puntos. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | El [`ISection`](/slides/python-net/es/aspose.slides/isection) referenciado por el marco Section Zoom; <br/><br/>            debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | El [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) a mostrar dentro del marco Section Zoom. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada si la sección referenciada no pertenece a la presentación actual o no contiene diapositivas. |



### Ver también
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ISection`](/slides/python-net/es/aspose.slides/isection)
* clase [`ISectionZoomFrame`](/slides/python-net/es/aspose.slides/isectionzoomframe)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)