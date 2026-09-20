---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Restituisce la miniatura della forma.  
ShapeThumbnailBounds.Shape tipo di delimitazione della miniatura della forma è usato per impostazione predefinita.

### Restituisce

miniatura di Shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Restituisce

miniatura di Shape o None nel caso in cui ShapeThumbnailBounds.Appearance sia usato e una forma non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di delimitazione della miniatura della forma. |
| scale_x | **float** | scala X |
| scale_y | **float** | scala Y |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`SectionZoomFrame`](/slides/python-net/it/aspose.slides/sectionzoomframe)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)