---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

### Returns

Yeni slayt.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |

### Remarks

Farklı sunumlar arasında bir slaytı kopyalarken slaytın master'ı da kopyalanabilir.  
İç kayıt defteri, aynı master slaytının birden çok kopyasının oluşturulmasını önlemek için otomatik olarak kopyalanan master'ları izlemek amacıyla kullanılır.  
Master slaytların manuel kopyalanması ne önlenmez ne de kaydedilir.  
Kopyalama süreci üzerinde daha fazla kontrol gerektirdiğinde şu API'leri kullanın  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** veya  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** slaytları kopyalamak için,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** veya  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** düzenleri kopyalamak için ve  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** master'ları kopyalamak için.



## add_clone(self, source_slide, section) {#islide-isection}
Belirtilen slaytın bir kopyasını belirtilen bölümün sonuna ekler.

### Returns

Yeni slayt.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Yeni slayt için bölüm. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

### Returns

Yeni slayt.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Belirtilen kaynak slaytın bir kopyasını koleksiyonun sonuna ekler.  
Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Tür veya Ad'a sahip olan düzenidir). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni (allowCloneMissingLayout true ise) kopyalanır veya (allowCloneMissingLayout false ise) PptxEditException fırlatılır.

### Returns

Yeni slayt.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni slayt için master slaytı. |
| allow_clone_missing_layout | **bool** | Belirtilen master'da uygun bir düzen bulunmadığında kaynak slaytın düzeni (allowCloneMissingLayout true ise) kopyalanır veya (allowCloneMissingLayout false ise) PptxEditException fırlatılır. |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Belirtilen master'da uygun bir düzen bulunmadığında ve allowCloneMissingLayout false olduğunda fırlatılır. |



### See Also
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* sınıf [`SlideCollection`](/slides/python-net/tr/aspose.slides/slidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)