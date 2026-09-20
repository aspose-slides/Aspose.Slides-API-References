---
title: remove_node method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Ta bort nod eller undernod efter index

```python
def remove_node(self, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Nollbaserat index för noden |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index är mindre än 0. -eller- index är lika med eller större än antal syskon |

## remove_node(self, node) {#ismartartnode}
Ta bort nod eller undernod

```python
def remove_node(self, node):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/sv/aspose.slides.smartart/ismartartnode) | Nod att ta bort |

### Se också
* klass [`ISmartArtNode`](/slides/python-net/sv/aspose.slides.smartart/ismartartnode)
* klass [`SmartArtNodeCollection`](/slides/python-net/sv/aspose.slides.smartart/smartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)