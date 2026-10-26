---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET API referenční příručka
description: 
type: docs
url: /cs/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Vrací miniaturu tvaru.
            ShapeThumbnailBounds.Shape typ omezení miniatury tvaru se používá jako výchozí.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ omezení miniatury tvaru. |
| scale_x | **float** | škála X |
| scale_y | **float** | škála Y |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`InkActions`](/slides/python-net/cs/aspose.slides.ink/inkactions)
* výčtový typ [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)