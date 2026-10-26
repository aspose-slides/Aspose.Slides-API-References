---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler.

### Dönüş

Yeni oluşturulan [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Summary Zoom çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, puan cinsinden. |

### Açıklamalar

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom çerçevesi oluşturur.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Sunumda bölüm bulunmuyorsa veya hedef slayt herhangi bir bölüme ait değilse atılır. |



### Bakınız
* sınıf [`ISummaryZoomFrame`](/slides/python-net/tr/aspose.slides/isummaryzoomframe)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)