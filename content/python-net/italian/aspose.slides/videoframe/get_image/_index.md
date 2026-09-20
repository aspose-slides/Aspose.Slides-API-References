---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Restituisce la miniatura della forma.  
ShapeThumbnailBounds.Shape è usato come tipo di limite per la miniatura della forma per impostazione predefinita.

### Restituisce

Miniatura della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce la miniatura della forma.

### Restituisce

Miniatura della forma o None nel caso in cui venga utilizzato ShapeThumbnailBounds.Appearance e la forma non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di limite per la miniatura della forma. |
| scale_x | **float** | scala X |
| scale_y | **float** | scala Y |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumerazione [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* classe [`VideoFrame`](/slides/python-net/it/aspose.slides/videoframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)