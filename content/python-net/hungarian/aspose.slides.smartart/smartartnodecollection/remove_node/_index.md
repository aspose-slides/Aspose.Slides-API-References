---
title: remove_node method
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Csomópont vagy alcsomópont eltávolítása index alapján


```python
def remove_node(self, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Nullától kezdődő index a csomóponthoz |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | az index kisebb, mint 0. -vagy- az index egyenlő vagy nagyobb, mint a testvérek száma |


## remove_node(self, node) {#ismartartnode}
Csomópont vagy alcsomópont eltávolítása


```python
def remove_node(self, node):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/hu/aspose.slides.smartart/ismartartnode) | Eltávolítandó csomópont |



### Lásd még
* osztály [`ISmartArtNode`](/slides/python-net/hu/aspose.slides.smartart/ismartartnode)
* osztály [`SmartArtNodeCollection`](/slides/python-net/hu/aspose.slides.smartart/smartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)