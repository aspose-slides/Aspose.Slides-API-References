---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
Vrací náhled tvaru.
            ShapeThumbnailBounds.Shape typ ohraničení náhledu tvaru se používá ve výchozím nastavení.

### Vrací

Náhled tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací náhled tvaru.

### Vrací

Náhled tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení náhledu tvaru. |
| scale_x | **float** | Měřítko X |
| scale_y | **float** | Měřítko Y |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* enumerace [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)