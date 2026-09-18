---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni OLE çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevenin yüksekliği, nokta cinsinden. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni OLE çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevenin yüksekliği, nokta cinsinden. |
| class_name | **str** | OLE nesnesinin sınıf adı. |
| path | **str** | Bağlantılı dosyanın yolu. <br/><br/>Bu yol sunumda olduğu gibi saklanır.<br/><br/>            Eğer bir göreceli yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez. |



### Bkz.
* sınıf [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)
* sınıf [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)