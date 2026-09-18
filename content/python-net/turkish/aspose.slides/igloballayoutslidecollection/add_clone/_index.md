---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Belirtilen düzen slaydının bir kopyasını sunuma ekler.

### Döndürür

Eklenen slayt.



```python
def add_clone(self, source_layout):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Kopyalanacak slayt. |

### Açıklamalar

Farklı sunumlar arasında bir düzeni kopyalarken, düzenin master slaytı da kaynak biçimlendirmesini korumak için kopyalanabilir. İç kayıt, aynı master slaydının birden çok kopyasının oluşturulmasını önlemek için otomatik olarak kopyalanan masterları izlemek üzere kullanılır. Master slaytların manuel kopyalanması ne önlenmez ne de kaydedilir.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Belirtilen düzen slaydının bir kopyasını sunuma ekler.

### Döndürür

Eklenen slayt.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide) | Kopyalanacak slayt. |
| dest_master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni düzen için master slayt. |

### Açıklamalar

Yeni düzen, hedef sunumdaki tanımlı master ile bağlanacaktır. Bu, PowerPoint'te "Use Destination Theme" seçeneğiyle kopyala/yapıştır işleminin eşdeğeridir.



### Ayrıca Bakınız
* sınıf [`IGlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/igloballayoutslidecollection)
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)