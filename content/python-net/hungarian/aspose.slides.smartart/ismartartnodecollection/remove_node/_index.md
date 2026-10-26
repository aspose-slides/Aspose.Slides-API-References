---
title: remove_node method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Eltávolítja a csomópontot vagy alcsomópontot index alapján.


```python
def remove_node(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | A csomópont nulla-alapú indexe |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | az index kisebb mint 0. -or- az index egyenlő vagy nagyobb, mint a testvérek száma. |


## remove_node(self, node_obj) {#ismartartnode}
Eltávolítja a csomópontot vagy alcsomópontot.


```python
def remove_node(self, node_obj):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/hu/aspose.slides.smartart/ismartartnode) | Eltávolítandó csomópont. |



### Lásd még
* osztály [`ISmartArtNode`](/slides/python-net/hu/aspose.slides.smartart/ismartartnode)
* osztály [`ISmartArtNodeCollection`](/slides/python-net/hu/aspose.slides.smartart/ismartartnodecollection)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)