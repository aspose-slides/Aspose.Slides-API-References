---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
            Se utiliza por defecto el tipo de límites de miniatura de forma ShapeThumbnailBounds.Shape.
### Devuelve

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve la miniatura de la forma.
### Devuelve

Shape thumbnail o None en caso de que se utilice ShapeThumbnailBounds.Appearance y una forma no tenga elementos visibles.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds) | Tipo de Shape thumbnail bounds. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |

### Ver también
* clase [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape)
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeración [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)