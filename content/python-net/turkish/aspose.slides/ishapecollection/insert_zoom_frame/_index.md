---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Yeni bir Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) Zoom çerçevesi tarafından referans edilen. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen slayt mevcut sunuma ait değilse atılır. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Önceden tanımlı bir görüntü ile yeni bir Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) Zoom çerçevesi tarafından referans edilen. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) referans verilen slayt için görüntü. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen slayt mevcut sunuma ait değilse atılır. |



### See Also
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)