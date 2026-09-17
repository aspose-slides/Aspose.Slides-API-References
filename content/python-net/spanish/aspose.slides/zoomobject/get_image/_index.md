---
title: get_image method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
            Se utiliza por defecto el tipo de límites de miniatura de forma ShapeThumbnailBounds.Shape.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds) | Tipo de límites de la miniatura de la forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeración [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* clase [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)