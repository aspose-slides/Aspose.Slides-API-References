---
title: remove_node method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Odstraní uzel nebo poduzel podle indexu.

```python
def remove_node(self, index):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index uzlu |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index je menší než 0.  -or- index je roven nebo větší než počet sourozenců. |

## remove_node(self, node_obj) {#ismartartnode}
Odstraní uzel nebo poduzel.

```python
def remove_node(self, node_obj):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode) | Uzel k odstranění. |

### Viz také
* třída [`ISmartArtNode`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode)
* třída [`ISmartArtNodeCollection`](/slides/python-net/cs/aspose.slides.smartart/ismartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)