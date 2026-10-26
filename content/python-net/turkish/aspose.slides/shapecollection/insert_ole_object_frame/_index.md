---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni OLE çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevenin yüksekliği, nokta cinsinden. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)). |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan OLE nesne çerçevesi.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni OLE çerçevenin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevenin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevenin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevenin yüksekliği, nokta cinsinden. |
| class_name | **str** | OLE nesnesinin sınıf adı. |
| path | **str** | Bağlantılı dosyanın yolu. <br/><br/>Bu yol sunumda olduğu gibi saklanır.<br/><br/>            Göreceli bir yol belirtilirse, dosya sunumu farklı bir dizinden açtığınızda erişilemez olacaktır. |

### Bakınız
* class [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe)
* class [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)