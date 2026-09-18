---
title: remove_node method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Düğümü veya alt düğümü indeksine göre kaldır.

```python
def remove_node(self, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Düğümün sıfır tabanlı indeksi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | indeks 0'dan küçüktür. -veya- indeks kardeş sayısına eşit ya da daha büyüktür. |

## remove_node(self, node_obj) {#ismartartnode}
Düğümü veya alt düğümü kaldır.

```python
def remove_node(self, node_obj):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/tr/aspose.slides.smartart/ismartartnode) | Kaldırılacak düğüm. |

### Ayrıca Bakınız
* sınıf [`ISmartArtNode`](/slides/python-net/tr/aspose.slides.smartart/ismartartnode)
* sınıf [`ISmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/ismartartnodecollection)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)