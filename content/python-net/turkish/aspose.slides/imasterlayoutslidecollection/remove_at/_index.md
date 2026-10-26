---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Koleksiyonun belirtilen dizinindeki öğeyi kaldırır.

```python
def remove_at(self, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Kaldırılacak öğenin sıfır tabanlı dizini. |

### Açıklamalar

1) PptxEditException hatasının atılmasını önlemek için önce layout'un HasDependingSlides özelliğini kontrol edin.
2) Kodu basitleştirmek için ayrıca [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) yöntemini de kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Layout sunumda kullanılıyorsa (HasDependingSlides özelliği true ise) atılır. |

### Ayrıca Bakınız
* sınıf [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)