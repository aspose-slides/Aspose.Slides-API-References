---
title: remove_node method
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Usuń węzeł lub podwęzeł według indeksu.

```python
def remove_node(self, index):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks węzła rozpoczynający się od zera |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index jest mniejszy niż 0. -lub- index jest równy lub większy niż liczba rodzeństwa. |

## remove_node(self, node_obj) {#ismartartnode}
Usuń węzeł lub podwęzeł.

```python
def remove_node(self, node_obj):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/pl/aspose.slides.smartart/ismartartnode) | Węzeł do usunięcia. |

### Zobacz również
* klasa [`ISmartArtNode`](/slides/python-net/pl/aspose.slides.smartart/ismartartnode)
* klasa [`ISmartArtNodeCollection`](/slides/python-net/pl/aspose.slides.smartart/ismartartnodecollection)
* moduł [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* biblioteka [`Aspose.Slides`](/slides/python-net)