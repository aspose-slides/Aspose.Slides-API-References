---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

### Döndürür

Yeni slayt.



```python
def add_clone(self, source_slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |

### Açıklama

Farklı sunumlar arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir.
            İç kayıt, aynı master slaytının birden fazla kopyasının oluşturulmasını önlemek için otomatik olarak klonlanan master'ları izlemek amacıyla kullanılır.
            Master slaytların manuel klonlanması ne engellenir ne de kaydedilir.
            Klonlama süreci üzerinde daha fazla kontrol gerektiyse şu yöntemleri kullanın
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
Belirtilen slaytın bir kopyasını belirtilen bölümün sonuna ekler.

### Döndürür

Yeni slayt.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |
| section | [`ISection`](/slides/python-net/tr/aspose.slides/isection) | Yeni slayt için bölüm. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

### Döndürür

Yeni slayt.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Belirtilen kaynak slaytın bir kopyasını koleksiyonun sonuna ekler.
            Uygun düzen, belirtilen master'dan otomatik olarak seçilir 
            (uygun düzen, kaynak slaytın düzeniyle aynı Tür veya Ad'a sahip düzendir). Eğer uygun bir düzen yoksa
            kaynak slaytın düzeni klonlanır (allowCloneMissingLayout true ise) ya da PptxEditException fırlatılır (allowCloneMissingLayout false ise).

### Döndürür

Yeni slayt.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allow_clone_missing_layout | **bool** | Eğer belirtilen master içinde uygun bir düzen yoksa, kaynak slaytın <br/><br/>            düzeni klonlanır (allowCloneMissingLayout true ise) ya da <br/><br/>            PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Belirtilen master içinde uygun bir düzen yoksa ve <br/>            allowCloneMissingLayout false ise fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* sınıf [`ISection`](/slides/python-net/tr/aspose.slides/isection)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`ISlideCollection`](/slides/python-net/tr/aspose.slides/islidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)