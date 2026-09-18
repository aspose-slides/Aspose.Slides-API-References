---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Yeni bir bağlayıcı şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler,
            varsayılan şablon stilini uygular.

### Döndürür

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Bağlayıcı şeklinin ekleneceği sıfır tabanlı indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcı çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcı çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcı çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcı çerçevesinin yüksekliği, nokta cinsinden. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Yeni bir bağlayıcı şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler,
            isteğe bağlı olarak varsayılan şablon stilini uygular.

### Döndürür

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Bağlayıcı şeklinin ekleneceği sıfır tabanlı indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcı çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcı çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcı çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcı çerçevesinin yüksekliği, nokta cinsinden. |
| create_from_template | **bool** | True – varsayılan şablon stilini uygulamak için (boş olmayan ad, basit stil);
<br/><br/>            false – bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için. |



### İlgili
* sınıf [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* enum [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)