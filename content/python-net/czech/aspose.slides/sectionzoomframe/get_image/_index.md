---
title: get_image method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            Typ ohraničení miniatury tvaru ShapeThumbnailBounds.Shape se používá jako výchozí.

### Vrací

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Vrací

Miniatura tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá žádné viditelné prvky.



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
* třída [`SectionZoomFrame`](/slides/python-net/cs/aspose.slides/sectionzoomframe)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)