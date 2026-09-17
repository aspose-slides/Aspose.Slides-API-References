---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
            Se utiliza el tipo de límites de miniatura de forma ShapeThumbnailBounds.Shape de forma predeterminada.

### Devuelve

Miniatura de forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve la miniatura de la forma.

### Devuelve

Miniatura de forma o None en caso de que se utilice ShapeThumbnailBounds.Appearance y una forma no tenga elementos visibles.



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
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeración [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* clase [`ZoomFrame`](/slides/python-net/es/aspose.slides/zoomframe)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)