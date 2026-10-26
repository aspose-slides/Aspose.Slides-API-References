---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen dizine ekler.

### Döndürür

Yeni oluşturulan [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe).

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Özet Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni Özet Zoom çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Yeni Özet Zoom çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Yeni Özet Zoom çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Yeni Özet Zoom çerçevesinin yüksekliği, nokta biriminde. |

### Açıklamalar

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom çerçevesi oluşturur.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Sunumda bölüm bulunmaması durumda ya da hedef slaytın herhangi bir bölüme ait olmaması durumunda fırlatılır. |

### Diğer Bağlantılar
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)