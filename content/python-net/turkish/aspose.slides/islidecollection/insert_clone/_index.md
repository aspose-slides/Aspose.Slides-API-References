---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |

### Açıklamalar

Farklı sunumlar arasında bir slaytı klonlarken slaytın ana teması da klonlanabilir.
İç kayıt defteri, otomatik olarak klonlanan temaları izlemek ve aynı ana slaytın birden fazla klonunun oluşturulmasını önlemek için kullanılır.
Ana slaytların manuel klonlanması ne engellenir ne de kaydedilir.
Klonlama süreci üzerinde daha fazla kontrol gerekiyorsa şunu kullanın
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** ya da
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** slaytları klonlamak için ve
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** temaları klonlamak için.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Yeni slayt için yerleşim slaydı. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Belirtilen bir kaynak slaydının kopyasını koleksiyonun belirtilen konumuna ekler.
            Uygun yerleşim, belirtilen 
            ana temadan otomatik olarak seçilir (uygun yerleşim, kaynak slaydın 
            yerleşimiyle aynı Tip veya Ad'a sahip yerleşimdir). Eğer uygun bir yerleşim yoksa
            kaynak slaydın yerleşimi klonlanacaktır (eğer allowCloneMissingLayout 
            doğru ise) ya da PptxEditException fırlatılacaktır (eğer allowCloneMissingLayout
            yanlış ise).

### Döndürür

Eklenen slayt.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| source_slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Kopyalanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni slayd için ana tema. |
| allow_clone_missing_layout | **bool** | Belirtilen ana temada uygun bir yerleşim yoksa ve <br/><br/>            allowCloneMissingLayout yanlış ise fırlatılır (eğer allowCloneMissingLayout <br/><br/>            true ise kaynak slaydın yerleşimi klonlanır). |

### İstisnalar

| Exception | Açıklama |
| :- | :- |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Belirtilen ana temada uygun bir yerleşim yoksa ve <br/>            allowCloneMissingLayout yanlış ise fırlatılır. |



### Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* sınıf [`ISlideCollection`](/slides/python-net/tr/aspose.slides/islidecollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)