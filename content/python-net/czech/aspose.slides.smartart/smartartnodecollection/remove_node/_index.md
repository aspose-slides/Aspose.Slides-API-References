---
title: remove_node method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Odstraňuje uzel nebo poduzel podle indexu


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index je menší než 0.  -or- index je roven nebo větší než počet sourozenců |


## remove_node(self, node) {#ismartartnode}
Odstraňuje uzel nebo poduzel


```python
def remove_node(self, node):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode) | Uzel k odstranění |



### Viz také
* třída [`ISmartArtNode`](/slides/python-net/cs/aspose.slides.smartart/ismartartnode)
* třída [`SmartArtNodeCollection`](/slides/python-net/cs/aspose.slides.smartart/smartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)