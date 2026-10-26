---
title: remove method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Sunumdan yerleşimi kaldırır.


```python
def remove(self):
    ...
```


### Açıklamalar

PptxEditException istisnasının atılmasını önlemek için layout'ın HasDependingSlides özelliğini önceden kontrol edin.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Sunumdan yerleşim zaten kaldırılmışsa veya yerleşim sunumda kullanılıyorsa (HasDependingSlides özelliği true ise) atılır. |

### İlgili
* sınıf [`LayoutSlide`](/slides/python-net/tr/aspose.slides/layoutslide)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)