---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Restituisce la miniatura della forma.
ShapeThumbnailBounds.Shape è il tipo di limiti della miniatura della forma usato per impostazione predefinita.

### Restituisce

Miniatura della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Restituisce

Miniatura della forma o None nel caso in cui ShapeThumbnailBounds.Appearance sia utilizzato e una forma non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di limiti della miniatura della forma. |
| scale_x | **float** | Scala X |
| scale_y | **float** | Scala Y |



### Vedi anche
* class [`GroupShape`](/slides/python-net/it/aspose.slides/groupshape)
* class [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)