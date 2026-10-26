---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Belirtilen indeksteki öğeyi bir koleksiyonda kaldırır.

```python
def remove_at(self, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | İndeks 0'dan küçüktür veya indeks Count değerine eşit ya da daha büyüktür |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Yorum zaten kaldırılmışsa fırlatılır. |

### İlgili
* sınıf [`ICommentCollection`](/slides/python-net/tr/aspose.slides/icommentcollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)