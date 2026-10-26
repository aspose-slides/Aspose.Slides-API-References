---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmini döndürür.
            ShapeThumbnailBounds.Shape şekil küçük resmi sınırlama türü varsayılan olarak kullanılır.

### Dönen Değer

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmini döndürür.

### Dönen Değer

Shape thumbnail veya ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında None.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Shape thumbnail sınır türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### Ayrıca Bakınız
* class [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* class [`SmartArt`](/slides/python-net/tr/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)