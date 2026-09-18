---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Yeni bir Section Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Dönüş

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Section Zoom frame'in ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Section Zoom frame'in x-koordinatı, puan cinsinden. |
| y | **float** | Yeni Section Zoom frame'in y-koordinatı, puan cinsinden. |
| width | **float** | Yeni Section Zoom frame'in genişliği, puan cinsinden. |
| height | **float** | Yeni Section Zoom frame'in yüksekliği, puan cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom frame tarafından referans edilen [`ISection`](/slides/python-net/tr/aspose.slides/isection);<br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Önceden tanımlı bir görüntü ile yeni bir Section Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

### Dönüş

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Section Zoom frame'in ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Section Zoom frame'in x-koordinatı, puan cinsinden. |
| y | **float** | Yeni Section Zoom frame'in y-koordinatı, puan cinsinden. |
| width | **float** | Yeni Section Zoom frame'in genişliği, puan cinsinden. |
| height | **float** | Yeni Section Zoom frame'in yüksekliği, puan cinsinden. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom frame tarafından referans edilen [`ISection`](/slides/python-net/tr/aspose.slides/isection);<br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Section Zoom frame içinde görüntülenecek resim. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)