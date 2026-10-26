---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Belirtilen bir düzen slaytının bir kopyasını koleksiyonun sonuna ekler.

### Returns
Eklenen slayt.



```python
def add_clone(self, source_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Klonlanacak slayt. |

### Remarks

1) Yeni düzen, bu düzen slaytları koleksiyonu için ana master slayt ile ilişkilendirilecektir.  
   Bu, PowerPoint'te "Use Destination Theme" seçeneğiyle kopyala/yapıştır işleminin bir eşdeğeridir.  
2) Bu yöntemin eşdeğeri, **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** özelliğiyle erişilen [`IPresentation.layout_slides`](/slides/python-net/tr/aspose.slides/ipresentation/layout_slides) özelliğidir.

### See Also
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)