---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Yeni bir otomatik şekil oluşturur, varsayılan biçimlendirme uygular ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x-koordinatı, nokta biriminde. |
| y | **float** | Şeklin çerçevesinin y-koordinatı, nokta biriminde. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta biriminde. |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

### Döndürür

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x-koordinatı, nokta biriminde. |
| y | **float** | Şeklin çerçevesinin y-koordinatı, nokta biriminde. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta biriminde. |
| create_from_template | **bool** | Yeni şekle varsayılan şablon stilini (basit stil, ortalanmış metin ve boş olmayan ad) uygulamak için true;<br/><br/>            yeni şekle; false ise şekli tüm özellikleri varsayılan değerlere ayarlayarak oluşturur. |

### Ayrıca
* sınıf [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)