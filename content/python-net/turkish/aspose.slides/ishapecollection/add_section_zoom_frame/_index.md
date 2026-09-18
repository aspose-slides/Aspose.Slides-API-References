---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).

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
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom çerçevesinin referans verdiği [`ISection`](/slides/python-net/tr/aspose.slides/isection); <br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Önceden tanımlı bir görüntü ile yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe).

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
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Section Zoom çerçevesinin referans verdiği [`ISection`](/slides/python-net/tr/aspose.slides/isection); <br/><br/>            bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Section Zoom çerçevesi içinde görüntülenecek [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage). |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referans verilen bölüm mevcut sunuma ait değilse veya slayt içermiyorsa fırlatılır. |

### Diğer Bağlantılar
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISectionZoomFrame`](/slides/python-net/tr/aspose.slides/isectionzoomframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)