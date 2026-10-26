---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Devuelve miniatura de forma.
            Se utiliza ShapeThumbnailBounds.Shape como tipo de límite de miniatura de forma por defecto.

### Devuelve
Miniatura de forma.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve miniatura de forma.

### Devuelve
Miniatura de forma o None en caso de que se use ShapeThumbnailBounds.Appearance y una forma no tenga elementos visibles.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |

### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`Ink`](/slides/python-net/es/aspose.slides.ink/ink)
* enumeración [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides.ink`](/slides/python-net/es/aspose.slides.ink)
* biblioteca [`Aspose.Slides`](/slides/python-net)