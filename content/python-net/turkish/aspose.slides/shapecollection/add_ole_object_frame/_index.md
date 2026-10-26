---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Dönüş Değeri

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo) | Gömülü OLE verisi hakkında bilgi ([`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Dönüş Değeri

Yeni oluşturulan [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| class_name | **str** | OLE nesnesinin sınıf adı. |
| path | **str** | Bağlantılı dosyanın yolu. <br/><br/>Bu yol sunum içinde olduğu gibi depolanır.<br/><br/>            Eğer bir göreceli yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez. |



### İlgili
* sınıf [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo)
* sınıf [`IOleObjectFrame`](/slides/python-net/tr/aspose.slides/ioleobjectframe)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)