---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            ShapeThumbnailBounds.Shape typ ohraničení miniatury tvaru se používá ve výchozím nastavení.

### Returns

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Returns

Miniatura tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení miniatury tvaru. |
| scale_x | **float** | Měřítko X |
| scale_y | **float** | Měřítko Y |



### See Also
* třída [`AutoShape`](/slides/python-net/cs/aspose.slides/autoshape)
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* enumerace [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)