---
title: remove method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Koleksiyondan bir yerleşimi kaldırır.


```python
def remove(self, value):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak yerleşim slaytı. |

### Açıklamalar

1) PptxEditException istisnasının atılmasını önlemek için, önce yerleşimin HasDependingSlides özelliğini kontrol edin.  
2) Kodu basitleştirmek için aynı zamanda [`ILayoutSlide.remove`](/slides/python-net/tr/aspose.slides/ilayoutslide/remove) yöntemini de kullanabilirsiniz.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Yerleşim bir sunumda kullanılmışsa (HasDependingSlides özelliği true ise) atılır. |



### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`ILayoutSlideCollection`](/slides/python-net/tr/aspose.slides/ilayoutslidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)