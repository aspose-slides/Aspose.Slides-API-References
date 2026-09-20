---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Vrací náhled tvaru.
            Typ ohraničení náhledu tvaru ShapeThumbnailBounds.Shape se používá jako výchozí.

### Návratová hodnota

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací náhled tvaru.

### Návratová hodnota

Shape thumbnail nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení náhledu tvaru. |
| scale_x | **float** | X měřítko |
| scale_y | **float** | Y měřítko |



### Viz také
* třída [`GroupShape`](/slides/python-net/cs/aspose.slides/groupshape)
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* výčtový typ [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)