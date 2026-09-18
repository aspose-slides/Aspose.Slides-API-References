---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Yeni bir Section Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| index | **int** | Section Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Section Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Section Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Section Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Section Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom çerçevesi tarafından referans verilen [`ISection`](/slides/python-net/tr/aspose.slides/isection);<br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### İstisnalar

| Exception | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm geçerli sunuma ait değilse veya slayt içermiyorsa fırlatılır. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Önceden tanımlı bir görüntüyle yeni bir Section Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| index | **int** | Section Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Section Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Section Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Section Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Section Zoom çerçevesinin yüksekliği, puan cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom çerçevesi tarafından referans verilen [`ISection`](/slides/python-net/tr/aspose.slides/isection);<br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Section Zoom çerçevesi içinde gösterilecek görüntü. |

### İstisnalar

| Exception | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm geçerli sunuma ait olmayan veya slayt içermiyorsa fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)