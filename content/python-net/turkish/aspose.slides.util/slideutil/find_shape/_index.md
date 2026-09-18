---
title: find_shape method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
PPTX sunumunda alternatif metne göre şekil bul.

### Döndürür

Şekil ya da None.



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) | Tarama yapılan sunum. |
| alt_text | **str** | Bir şeklin alternatif metni. |


## find_shape(slide, alt_text) {#ibaseslide-str}
PPTX sunumunda bir slaytta alternatif metne göre şekil bul.

### Döndürür

Şekil ya da None.



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide) | Tarama yapılan slayt. |
| alt_text | **str** | Bir şeklin alternatif metni. |



### İlgili
* sınıf [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* sınıf [`SlideUtil`](/slides/python-net/tr/aspose.slides.util/slideutil)
* modül [`aspose.slides.util`](/slides/python-net/tr/aspose.slides.util)
* kütüphane [`Aspose.Slides`](/slides/python-net)