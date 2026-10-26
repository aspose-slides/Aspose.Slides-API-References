---
title: remove_node method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Ta bort nod eller undernod med index.

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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index är mindre än 0.  -eller- index är lika med eller större än antalet syskon. |

## remove_node(self, node_obj) {#ismartartnode}
Ta bort nod eller undernod.

```python
def remove_node(self, node_obj):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/sv/aspose.slides.smartart/ismartartnode) | Nod som ska tas bort. |

### Se även
* klass [`ISmartArtNode`](/slides/python-net/sv/aspose.slides.smartart/ismartartnode)
* klass [`ISmartArtNodeCollection`](/slides/python-net/sv/aspose.slides.smartart/ismartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)