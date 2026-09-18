---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmi döndürür.
            Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır.

### Döndürür

Şekil küçük resmi.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmi döndürür.

### Döndürür

ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında şekil küçük resmi veya None döndürülür.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resmi sınır tipi. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)