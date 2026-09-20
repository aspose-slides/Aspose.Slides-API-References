---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            ShapeThumbnailBounds.Shape typ ohraničení miniatury tvaru se používá jako výchozí.

### Návrat

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Návrat

Miniatura tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení miniatury tvaru. |
| scale_x | **float** | škála X |
| scale_y | **float** | škála Y |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* enumerace [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* třída [`SmartArtShape`](/slides/python-net/cs/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)