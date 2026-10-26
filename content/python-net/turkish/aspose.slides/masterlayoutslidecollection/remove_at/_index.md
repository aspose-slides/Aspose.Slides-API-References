---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Koleksiyonun belirtilen indisindeki öğeyi kaldırır.

```python
def remove_at(self, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Öğenin kaldırılacağı sıfırdan başlayan indis. |

### Açıklamalar

1) PptxEditException'ın atılmasını önlemek için önceden layout'un HasDependingSlides özelliğini kontrol edin.  
2) Kodu basitleştirmek için aynı zamanda [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) yöntemini de kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Sunumda layout kullanılırsa (HasDependingSlides özelliği true ise) fırlatılır. |

### Bakınız
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)