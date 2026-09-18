---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Yeni bir bağlayıcı şekli oluşturur, varsayılan şablon stilini uygular ve şekil koleksiyonunun sonuna ekler.

### Dönüş

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Eklemek için bağlayıcı şeklinin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)'ı. |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta cinsinden. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Yeni bir bağlayıcı şekli oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

### Dönüş

Yeni oluşturulan [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | Oluşturulacak bağlayıcı şeklinin [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)'ı. |
| x | **float** | Bağlayıcının çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Bağlayıcının çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Bağlayıcının çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Bağlayıcının çerçevesinin yüksekliği, nokta cinsinden. |
| create_from_template | **bool** | Varsayılan şablon stilini (boş olmayan ad, basit stil) uygulamak için true; <br/><br/>            Bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için false. |



### Ayrıca Bakınız
* sınıf [`IConnector`](/slides/python-net/tr/aspose.slides/iconnector)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* enum [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)