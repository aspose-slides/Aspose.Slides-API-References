---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides/summaryzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            Ve výchozím nastavení se používá typ hranic miniatury tvaru ShapeThumbnailBounds.Shape.

### Vrací

Miniatura tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací miniaturu tvaru.

### Vrací

Miniatura tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ hranic miniatury tvaru. |
| scale_x | **float** | Měřítko X |
| scale_y | **float** | Měřítko Y |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* enumerace [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* třída [`SummaryZoomFrame`](/slides/python-net/cs/aspose.slides/summaryzoomframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)