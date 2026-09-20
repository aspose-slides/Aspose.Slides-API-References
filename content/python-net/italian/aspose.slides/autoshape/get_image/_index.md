---
title: get_image method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Restituisce la miniatura della forma.
            Il tipo di limiti della miniatura della forma ShapeThumbnailBounds.Shape è usato per impostazione predefinita.

### Returns

Miniatura della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Returns

Miniatura della forma o None nel caso in cui venga utilizzato ShapeThumbnailBounds.Appearance e una forma non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di limiti della miniatura della forma. |
| scale_x | **float** | Scala X |
| scale_y | **float** | Scala Y |



### See Also
* classe [`AutoShape`](/slides/python-net/it/aspose.slides/autoshape)
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)