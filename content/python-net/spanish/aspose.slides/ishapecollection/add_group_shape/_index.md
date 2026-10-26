---
title: add_group_shape method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas.  
El marco del grupo se ajustará automáticamente para adaptarse a cualquier forma añadida.

### Devuelve
El [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape) recién creado.

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas.

### Devuelve
El [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape) recién creado.

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) | El [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) que contiene contenido vectorial para convertir en formas. |
| x | **float** | La coordenada x del marco del grupo, en puntos. |
| y | **float** | La coordenada y del marco del grupo, en puntos. |
| width | **float** | El ancho del marco del grupo, en puntos. |
| height | **float** | La altura del marco del grupo, en puntos. |

### Ver también
* clase [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* clase [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)