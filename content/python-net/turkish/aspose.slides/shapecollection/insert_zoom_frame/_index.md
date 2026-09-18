---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Yeni bir Zoom frame oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Zoom frame'in ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Zoom frame'in x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom frame'in y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom frame'in genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom frame'in yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Zoom frame tarafından başvurulan [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen slayt mevcut sunuma dahil değilse fırlatılır. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Önceden tanımlı bir görüntü ile yeni bir Zoom frame oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Zoom frame'in ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Zoom frame'in x koordinatı, puan cinsinden. |
| y | **float** | Yeni Zoom frame'in y koordinatı, puan cinsinden. |
| width | **float** | Yeni Zoom frame'in genişliği, puan cinsinden. |
| height | **float** | Yeni Zoom frame'in yüksekliği, puan cinsinden. |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Zoom frame tarafından başvurulan [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Referans verilen slayt [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) için görüntü. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen slayt mevcut sunuma dahil değilse fırlatılır. |



### Ayrıca Bakınız
* class [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* class [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/tr/aspose.slides/izoomframe)
* class [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)