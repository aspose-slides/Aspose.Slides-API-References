---
title: remove method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Koleksiyondan bir düzeni kaldırır.


```python
def remove(self, value):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak düzen slaydı. |

### Açıklamalar

1) PptxEditException'ın fırlatılmasını önlemek için önce düzenin HasDependingSlides özelliğini kontrol edin.  
2) Kodu basitleştirmek için ayrıca [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) yöntemini kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Düzen sunumda kullanılıyorsa (HasDependingSlides özelliği true ise) fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)