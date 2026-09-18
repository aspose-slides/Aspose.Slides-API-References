---
title: remove method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Koleksiyondan bir düzeni kaldırır.

```python
def remove(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak düzen slaytı. |

### Açıklamalar

1) PptxEditException'ın fırlatılmasını önlemek için layout'un HasDependingSlides özelliğini önceden kontrol edin.
2) Kodu basitleştirmek için ayrıca [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) metodunu kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Düzen sunumda kullanılıyorsa (HasDependingSlides özelliği true ise) fırlatılır. |

### Ayrıca Bakınız
* sınıf [`GlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/globallayoutslidecollection)
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)