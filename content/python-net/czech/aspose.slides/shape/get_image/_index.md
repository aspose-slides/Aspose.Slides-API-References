---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Vrací náhled tvaru.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Vrací

Náhled tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací náhled tvaru.

### Vrací

Náhled tvaru nebo None v případě, že je použita ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



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
* class [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* class [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)