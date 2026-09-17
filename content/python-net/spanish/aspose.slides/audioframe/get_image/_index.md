---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Devuelve la miniatura de la forma.
            ShapeThumbnailBounds.Shape tipo de límites de miniatura de forma se usa por defecto.

### Devuelve

Miniatura de forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Devuelve la miniatura de la forma.

### Devuelve

Miniatura de forma o None en caso de que se use ShapeThumbnailBounds.Appearance y una forma no tenga elementos visibles.



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
* class [`AudioFrame`](/slides/python-net/es/aspose.slides/audioframe)
* class [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/es/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)