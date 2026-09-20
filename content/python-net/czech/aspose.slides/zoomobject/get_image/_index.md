---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/zoomobject/get_image/
weight: 30
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



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* výčet [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* třída [`ZoomObject`](/slides/python-net/cs/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)