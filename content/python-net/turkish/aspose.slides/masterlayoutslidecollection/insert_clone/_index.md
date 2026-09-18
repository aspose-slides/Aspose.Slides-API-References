---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Belirtilen bir yerleşim slaytının bir kopyasını, koleksiyonun belirtilen konumuna ekler.

### Döndürür

Eklenen slayt.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Klonlanacak slayt. |

### Açıklamalar

Yeni yerleşim, bu yerleşim slayt koleksiyonu için ana master slayt ile bağlantılı olacaktır.
            Bu nedenle PowerPoint'te "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştırın eşdeğeridir.

### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)