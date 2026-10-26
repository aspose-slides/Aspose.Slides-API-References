---
title: get_image method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Restituisce shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type viene usato per impostazione predefinita.

### Restituisce

shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce shape thumbnail.

### Restituisce

shape thumbnail o None nel caso in cui ShapeThumbnailBounds.Appearance è usato e una shape non ha elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | scala X |
| scale_y | **float** | scala Y |



### Vedi anche
* classe [`AudioFrame`](/slides/python-net/it/aspose.slides/audioframe)
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)