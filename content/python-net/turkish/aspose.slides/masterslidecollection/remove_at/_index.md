---
title: remove_at method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Koleksiyonun belirtilen indeksindeki öğeyi kaldırır.


```python
def remove_at(self, index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### Açıklamalar

PptxEditException istisnasının atılmasını önlemek için önce masterın HasDependingSlides özelliğini kontrol edin.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Kaldırılacak master sunumda kullanılıyorsa (HasDependingSlides özelliği true ise) fırlatılır. |



### Ayrıca Bakınız
* sınıf [`MasterSlideCollection`](/slides/python-net/tr/aspose.slides/masterslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)