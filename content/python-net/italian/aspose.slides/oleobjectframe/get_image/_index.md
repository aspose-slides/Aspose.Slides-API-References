---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
Restituisce la miniatura della forma.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Restituisce

Miniatura della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Restituisce

Miniatura della forma o None nel caso in cui venga utilizzato ShapeThumbnailBounds.Appearance e una forma non abbia elementi visibili.



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
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`OleObjectFrame`](/slides/python-net/it/aspose.slides/oleobjectframe)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)