---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler.

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |

### Açıklamalar

Farklı sunumlar arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir.  
İç kayıt, otomatik olarak klonlanan master'ları izlemek için kullanılır ve aynı master slaydının birden fazla klonunun oluşturulmasını önler.  
Master slaytların manuel klonlanması ne önlenir ne de kaydedilir.  
Klonlama süreci üzerinde daha fazla kontrol gerekirse şu yöntemler kullanılabilir:  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** veya  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** slaytların klonlanması için ve  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** masterların klonlanması için.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler.

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Yeni slayt için düzen slaydı. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Belirtilen kaynak slayttan bir kopyayı koleksiyonun belirtilen konumuna ekler.  
Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaydın türü veya adıyla aynı olan düzen olur). Uygun bir düzen bulunamazsa, kaynak slaydın düzeni (allowCloneMissingLayout true ise) klonlanır veya (allowCloneMissingLayout false ise) PptxEditException fırlatılır.

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Klonlanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allow_clone_missing_layout | **bool** | Belirtilen master içinde uygun bir düzen yoksa kaynak slaydın düzeni <br/><br/>            klonlanır (allowCloneMissingLayout true ise) veya <br/><br/>            PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Belirtilen master içinde uygun bir düzen yoksa ve <br/>            allowCloneMissingLayout false ise fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* sınıf [`SlideCollection`](/slides/python-net/tr/aspose.slides/slidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)