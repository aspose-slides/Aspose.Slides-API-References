---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, nokta cinsinden. |

### Açıklamalar

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom çerçevesi oluşturur.

### İstisnalar

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Sunumda bölüm bulunmuyorsa veya hedef slayt herhangi bir bölüme ait değilse fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* sınıf [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)