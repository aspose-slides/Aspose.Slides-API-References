---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Belirtilen görseli içeren yeni bir resim çerçevesi oluşturur ve bunu şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IPictureFrame`](/slides/python-net/tr/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) içinde bulunan şekil türünü belirler,<br/><br/>            tüm çizgi türleri hariç:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Resim çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Resim çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Resim çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Resim çerçevesinin yüksekliği, puan cinsinden. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Resim çerçevesinde görüntülenecek [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage). |



### Ayrıca Bakınız
* sınıf [`IPictureFrame`](/slides/python-net/tr/aspose.slides/ipictureframe)
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* enumerasyon [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)