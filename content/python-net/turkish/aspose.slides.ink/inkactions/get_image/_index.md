---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmi döndürür.  
ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır.

### Döndürür

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmi döndürür.

### Döndürür

ShapeThumbnailBounds.Appearance kullanıldığında ve şeklin görünür öğeleri olmadığında Shape thumbnail veya None döndürülür.



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
* class [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* class [`InkActions`](/slides/python-net/tr/aspose.slides.ink/inkactions)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)