---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Zoom çerçevesi tarafından referans alınan [`ISlide`](/slides/python-net/tr/aspose.slides/islide);<br/><br/>            bu sunuma ait olmalıdır. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans alınan slayt mevcut sunuma ait değilse atılır. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom çerçevesinin yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Zoom çerçevesi tarafından referans alınan [`ISlide`](/slides/python-net/tr/aspose.slides/islide);<br/><br/>            bu sunuma ait olmalıdır. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Referans alınan slayt [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) için görüntü. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans alınan slayt mevcut sunuma ait değilse atılır. |



### Ayrıca Bakınız
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)