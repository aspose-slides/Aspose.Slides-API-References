---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            Výchozí je použita hodnota typu ohraničení miniatury tvaru.

### Vrací

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Vrací

Miniatura tvaru nebo None v případě, že je použita ShapeThumbnailBounds.Appearance a tvar nemá viditelné elementy.



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
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* enumerace [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* třída [`Table`](/slides/python-net/cs/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)