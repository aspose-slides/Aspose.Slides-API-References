---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Şekil küçük resmi döndürür.
ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır.

### Döndürür

Şekil küçük resmi.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmi döndürür.

### Döndürür

Shape thumbnail veya None, ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında döndürülür.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resmi sınırları türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### Ayrıca Bakınız
* sınıf [`Connector`](/slides/python-net/tr/aspose.slides/connector)
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)