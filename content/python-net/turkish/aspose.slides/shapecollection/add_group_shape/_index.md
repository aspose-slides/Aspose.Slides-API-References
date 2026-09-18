---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Yeni bir boş grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler.
Grup çerçevesi, eklenen tüm şekillere sığacak şekilde otomatik olarak ayarlanır.

### Döndürür

Yeni oluşturulan [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape).

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape).

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) | Şekillere dönüştürülecek vektör içeriğini içeren [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage). |
| x | **float** | Grup çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Grup çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Grup çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Grup çerçevesinin yüksekliği, nokta cinsinden. |

### Ayrıca Bakınız
* sınıf [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape)
* sınıf [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kitaplık [`Aspose.Slides`](/slides/python-net)