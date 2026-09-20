---
title: get_image method
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
Vrací náhled tvaru. Typ ohraničení náhledu tvaru ShapeThumbnailBounds.Shape je ve výchozím nastavení používán.

### Návrat
Náhled tvaru.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Vrací náhled tvaru.

### Návrat
Náhled tvaru nebo None v případě, že je použito ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds) | Typ ohraničení náhledu tvaru. |
| scale_x | **float** | Škála X |
| scale_y | **float** | Škála Y |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`OleObjectFrame`](/slides/python-net/cs/aspose.slides/oleobjectframe)
* výčtový typ [`ShapeThumbnailBounds`](/slides/python-net/cs/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)