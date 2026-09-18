---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler.
Grup çerçevesi, eklenen şekillere uyacak şekilde otomatik olarak ayarlanacaktır.

### Döndürür

Yeni oluşturulan [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü bireysel şekillere dönüştürür
ve oluşan grubu şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) | Şekillere dönüştürülmek üzere vektör içeriğini içeren [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage). |
| x | **float** | Grup çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Grup çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Grup çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Grup çerçevesinin yüksekliği, puan cinsinden. |



### Ayrıca Bakınız
* sınıf [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)