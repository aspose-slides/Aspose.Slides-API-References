---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
İndeks ile düğüm veya alt düğümü kaldır


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | indeks 0'dan küçüktür. -veya- indeks kardeş sayısına eşit veya daha büyüktür |


## remove_node(self, node) {#ismartartnode}
Düğüm veya alt düğümü kaldır


```python
def remove_node(self, node):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/tr/aspose.slides.smartart/ismartartnode) | Kaldırılacak düğüm |



### Ayrıca Bakınız
* sınıf [`ISmartArtNode`](/slides/python-net/tr/aspose.slides.smartart/ismartartnode)
* sınıf [`SmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/smartartnodecollection)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)