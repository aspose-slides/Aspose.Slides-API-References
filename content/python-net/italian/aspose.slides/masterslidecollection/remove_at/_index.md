---
title: remove_at method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Rimuove l'elemento all'indice specificato della collezione.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice a base zero dell'elemento da rimuovere. |

### Osservazioni

Per evitare il lancio di PptxEditException, controlla prima la proprietà HasDependingSlides del master.

### Eccezioni

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se il master da rimuovere è utilizzato nella presentazione (la sua proprietà HasDependingSlides è true). |

### Vedi anche
* classe [`MasterSlideCollection`](/slides/python-net/it/aspose.slides/masterslidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)