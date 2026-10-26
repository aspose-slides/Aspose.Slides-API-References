---
title: remove_node method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Hapus node atau sub node berdasarkan indeks


```python
def remove_node(self, index):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol dari node |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | indeks kurang dari 0. -atau- indeks sama dengan atau lebih besar dari jumlah saudara |


## remove_node(self, node) {#ismartartnode}
Hapus node atau sub node


```python
def remove_node(self, node):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/id/aspose.slides.smartart/ismartartnode) | Node yang akan dihapus |



### Lihat Juga
* kelas [`ISmartArtNode`](/slides/python-net/id/aspose.slides.smartart/ismartartnode)
* kelas [`SmartArtNodeCollection`](/slides/python-net/id/aspose.slides.smartart/smartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* pustaka [`Aspose.Slides`](/slides/python-net)