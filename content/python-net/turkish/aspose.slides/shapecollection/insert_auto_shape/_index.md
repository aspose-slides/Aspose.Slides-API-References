---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Yeni bir otomatik şekil oluşturur ve belirtilen indiste şekil koleksiyonuna ekler,
            varsayılan şablon biçimlendirmesini uygular.

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
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Yeni bir otomatik şekil oluşturur ve belirtilen indiste şekil koleksiyonuna ekler,
            isteğe bağlı olarak varsayılan şablon stilini uygulayarak başlatır.

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
| x | **float** | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| create_from_template | **bool** | Varsayılan şablon stilini uygulamak için True (boş olmayan bir ad, basit stil ve ortalanmış metin dahil); <br/><br/>false ile tüm özellikleri varsayılanlarına ayarlayarak şekli oluşturur. |



### Ayrıca Bakınız
* sınıf [`IAutoShape`](/slides/python-net/tr/aspose.slides/iautoshape)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* enum [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)