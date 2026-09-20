---
title: remove_node method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Hapus node atau sub node berdasarkan indeks.

```python
def remove_node(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol dari node |

### Pengecualian

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | indeks kurang dari 0. -or- indeks sama dengan atau lebih besar dari jumlah saudara. |

## remove_node(self, node_obj) {#ismartartnode}
Hapus node atau sub node.

```python
def remove_node(self, node_obj):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/id/aspose.slides.smartart/ismartartnode) | Node yang akan dihapus. |

### Lihat Juga
* class [`ISmartArtNode`](/slides/python-net/id/aspose.slides.smartart/ismartartnode)
* class [`ISmartArtNodeCollection`](/slides/python-net/id/aspose.slides.smartart/ismartartnodecollection)
* module [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)