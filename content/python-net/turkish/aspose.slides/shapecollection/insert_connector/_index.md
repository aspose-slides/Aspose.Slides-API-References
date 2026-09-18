---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Yeni bir bağlayıcı şekli oluşturur ve belirtilen indekste şekil koleksiyonuna ekler,
            varsayılan şablon stilini uygular.

### Returns

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Bağlayıcı şeklin ekleneceği sıfırdan başlayan indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta biriminde. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Yeni bir bağlayıcı şekli oluşturur ve belirtilen indekste şekil koleksiyonuna ekler,
            isteğe bağlı olarak varsayılan şablon stilini uygular.

### Returns

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Bağlayıcı şeklin ekleneceği sıfırdan başlayan indeks. |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklenecek bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta biriminde. |
| create_from_template | **bool** | True varsayılan şablon stilini uygular (boş olmayan ad, basit stil);<br/><br/>            false bağlayıcıyı varsayılan özellik değerleriyle oluşturur. |



### See Also
* sınıf [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* enumerasyon [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)