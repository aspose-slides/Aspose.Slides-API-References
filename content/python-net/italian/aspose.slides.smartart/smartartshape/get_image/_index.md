---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Restituisce l'anteprima della forma.  
Il tipo ShapeThumbnailBounds.Shape per i limiti dell'anteprima della forma è usato per impostazione predefinita.

### Restituisce

Anteprima della forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Restituisce l'anteprima della forma.

### Restituisce

Anteprima della forma o None nel caso in cui venga utilizzato ShapeThumbnailBounds.Appearance e la forma non abbia elementi visibili.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds) | Tipo di limiti dell'anteprima della forma. |
| scale_x | **float** | scala X |
| scale_y | **float** | scala Y |



### Vedi anche
* class [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/it/aspose.slides/shapethumbnailbounds)
* class [`SmartArtShape`](/slides/python-net/it/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/it/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)