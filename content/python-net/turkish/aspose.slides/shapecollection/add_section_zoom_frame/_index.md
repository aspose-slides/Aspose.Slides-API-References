---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | [`ISection`](/slides/python-net/tr/aspose.slides/isection)'ye başvuran Section Zoom çerçevesi; <br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### Exceptions

| Exception | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Başvurulan bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Önceden tanımlanmış bir görüntü ile yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | [`ISection`](/slides/python-net/tr/aspose.slides/isection)'ye başvuran Section Zoom çerçevesi; <br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Section Zoom çerçevesi içinde görüntülenecek [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage). |

### Exceptions

| Exception | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Başvurulan bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)