---
title: add_clone method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Belirtilen bir düzen slaytının bir kopyasını koleksiyonun sonuna ekler.

### Dönen Değer

Eklenen slayt.

```python
def add_clone(self, source_layout):
    ...
```

| Parametre | Tip | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Kopyalanacak slayt. |

### Açıklamalar

1) Yeni düzen, bu düzen slaytları koleksiyonunun ana master slaytı ile ilişkilendirilecektir.  
   Bu, PowerPoint'te "Use Destination Theme" seçeneği ile kopyala/yapıştır işleminin bir benzeridir.  
2) Bu yöntemin benzeri, [`IPresentation.layout_slides`](/slides/python-net/tr/aspose.slides/ipresentation/layout_slides) özelliğiyle erişilen **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** yöntemidir.

### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)