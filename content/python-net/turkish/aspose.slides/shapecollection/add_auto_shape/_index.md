---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Yeni bir otomatik şekil oluşturur, varsayılan biçimlendirmeyle ve şekil koleksiyonunun sonuna ekler.

### Returns

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

### Returns

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |
| create_from_template | **bool** | Doğru ise yeni şekle varsayılan şablon stilini (basit stil, ortalanmış metin ve boş olmayan ad) uygular;<br/><br/>            false ise tüm özellikleri varsayılan değerlere ayarlanmış şekilde şekli oluşturur. |



### See Also
* sınıf [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* enumerasyon [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)