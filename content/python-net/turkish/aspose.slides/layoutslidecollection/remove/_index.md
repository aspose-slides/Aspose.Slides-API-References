---
title: remove method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/layoutslidecollection/remove/
weight: 20
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

1) PptxEditException istisnasının atılmasını önlemek için layout'ın HasDependingSlides özelliğini önceden kontrol edin.  
2) Kodu basitleştirmek için aynı zamanda [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) yöntemini kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Düzen, sunumda kullanılıyorsa (HasDependingSlides özelliği doğru) atılır. |



### Bkz
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`LayoutSlideCollection`](/slides/python-net/tr/aspose.slides/layoutslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)