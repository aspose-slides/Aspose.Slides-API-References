---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Restituisce la miniatura della shape.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type viene usato per impostazione predefinita.

### Restituisce

Miniatura della Shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della shape.

### Restituisce

Miniatura della Shape o None nel caso in cui venga usato ShapeThumbnailBounds.Appearance e una shape non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di delimitazione della miniatura della Shape. |
| scale_x | **float** | Scala X |
| scale_y | **float** | Scala Y |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`InkActions`](/slides/python-net/it/aspose.slides.ink/inkactions)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides.ink`](/slides/python-net/it/aspose.slides.ink)
* libreria [`Aspose.Slides`](/slides/python-net)