---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

### Döndürür

Eklenen slayt.



```python
def add_clone(self, source_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Klonlanacak slayt. |

### Açıklamalar

Farklı sunumlar arasında bir yerleşim kopyalanırken yerleşimin ana slaytı da kaynak biçimlendirmesini korumak için kopyalanabilir. İç kayıt, otomatik olarak kopyalanan ana slaytları izlemek ve aynı ana slaytın birden fazla kopyasının oluşturulmasını önlemek için kullanılır. Ana slaytların manuel olarak kopyalanması ne engellenir ne de kaydedilir.



## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

### Döndürür

Eklenen slayt.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Klonlanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni bir yerleşim için ana slayt. |

### Açıklamalar

1) Yeni yerleşim, hedef sunumdaki tanımlı ana slayt ile ilişkilendirilecektir. Bu, PowerPoint'te “Use Destination Theme” seçeneğiyle kopyala/yapıştır işleminin bir benzeri olarak kabul edilir.  
2) Bu yöntemin benzeri, [`IMasterSlide.layout_slides`](/slides/python-net/tr/aspose.slides/imasterslide/layout_slides) özelliğiyle erişilen **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** yöntemidir.



### Ayrıca Bakınız
* sınıf [`GlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/globallayoutslidecollection)
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)