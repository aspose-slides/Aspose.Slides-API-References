---
title: remove_node method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Rimuovi il nodo o il sotto-nodo per indice


```python
def remove_node(self, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice basato su zero del nodo |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | l'indice è inferiore a 0.  -or- l'indice è uguale a o maggiore del conteggio dei fratelli |


## remove_node(self, node) {#ismartartnode}
Rimuovi il nodo o il sotto-nodo


```python
def remove_node(self, node):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/it/aspose.slides.smartart/ismartartnode) | Nodo da rimuovere |



### Vedi anche
* classe [`ISmartArtNode`](/slides/python-net/it/aspose.slides.smartart/ismartartnode)
* classe [`SmartArtNodeCollection`](/slides/python-net/it/aspose.slides.smartart/smartartnodecollection)
* modulo [`aspose.slides.smartart`](/slides/python-net/it/aspose.slides.smartart)
* libreria [`Aspose.Slides`](/slides/python-net)