---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
            Se usa el tipo de límites ShapeThumbnailBounds.Shape por defecto.

### Devuelve

Miniatura de la forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve la miniatura de la forma.

### Devuelve

Miniatura de la forma o None en caso de que se use ShapeThumbnailBounds.Appearance y la forma no tenga elementos visibles.



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
* class [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* class [`SummaryZoomSection`](/slides/python-net/es/aspose.slides/summaryzoomsection)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)