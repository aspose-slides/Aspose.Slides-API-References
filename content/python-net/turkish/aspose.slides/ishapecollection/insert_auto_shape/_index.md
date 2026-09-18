---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Yeni bir otomatik şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular.

### Döndürür

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Yeni bir otomatik şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini başlatır.

### Döndürür

Yeni oluşturulan [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek otomatik şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |
| create_from_template | **bool** | Varsayılan şablon stilini uygulamak için True (boş olmayan bir ad, basit stil ve ortalanmış metin dahil); şekli tüm özellikleri varsayılan değerlerine ayarlanmış olarak oluşturmak için false. |



### Ayrıca Bakınız
* sınıf [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)