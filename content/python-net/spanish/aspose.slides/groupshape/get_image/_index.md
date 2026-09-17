---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
ShapeThumbnailBounds.Shape se usa como tipo de límites de miniatura de forma por defecto.

### Devuelve

Miniatura de la forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve la miniatura de la forma.

### Devuelve

Miniatura de la forma o None en caso de que se utilice ShapeThumbnailBounds.Appearance y una forma no tenga elementos visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds) | Tipo de límites de miniatura de forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Ver también
* clase [`GroupShape`](/slides/python-net/es/aspose.slides/groupshape)
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeración [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)