---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            ShapeThumbnailBounds.Shape typ ohraničení miniatury tvaru je ve výchozím nastavení použit.

### Návrat

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Návrat

Shape thumbnail nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení miniatury tvaru. |
| scale_x | **float** | X měřítko |
| scale_y | **float** | Y měřítko |



### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* výčet [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)