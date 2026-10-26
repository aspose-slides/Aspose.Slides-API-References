---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| class_name | **str** | OLE nesnesinin sınıf adı. |
| path | **str** | Bağlı dosyanın yolu. <br/><br/>Bu yol sunumda olduğu gibi saklanır.<br/><br/>Bir göreli yol belirtilirse, sunumu farklı bir dizinden açtığınızda dosyaya erişilemez. |



### İlgili
* sınıf [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)
* sınıf [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)