---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Restituisce la miniatura della forma.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type è usato per impostazione predefinita.

### Restituisce

Miniatura della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Restituisce

Miniatura della forma o None nel caso in cui ShapeThumbnailBounds.Appearance è usato e una forma non ha elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di limite della miniatura della forma. |
| scale_x | **float** | scala X |
| scale_y | **float** | scala Y |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`Ink`](/slides/python-net/it/aspose.slides.ink/ink)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides.ink`](/slides/python-net/it/aspose.slides.ink)
* libreria [`Aspose.Slides`](/slides/python-net)