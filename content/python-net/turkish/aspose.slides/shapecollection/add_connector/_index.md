---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Yeni bir bağlayıcı şekli oluşturur, varsayılan şablon stilini uygular ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklemek için bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta cinsinden. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Yeni bir bağlayıcı şekli oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

### Döndürür

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Oluşturmak için bağlayıcı şeklin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta cinsinden. |
| create_from_template | **bool** | True bağlayıcıya varsayılan şablon stilini (boş olmayan ad, basit stil) uygular; <br/><br/>            false bağlayıcıyı varsayılan özellik değerleriyle oluşturur. |



### İlgili
* sınıf [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)