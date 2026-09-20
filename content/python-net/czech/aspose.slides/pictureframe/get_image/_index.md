---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
Vrací miniaturu tvaru.
ShapeThumbnailBounds.Shape typ ohraničení miniatury tvaru se používá jako výchozí.

### Návratová hodnota

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Návratová hodnota

Miniatura tvaru nebo None v případě, že je použit ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



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
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* výčet [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)