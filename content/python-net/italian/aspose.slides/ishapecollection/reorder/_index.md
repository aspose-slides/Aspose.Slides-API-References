---
title: reorder method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Sposta la forma specificata in una nuova posizione all’interno della collezione di forme.

```python
def reorder(self, index, shape):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L’indice target a base zero dove la forma sarà posizionata. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da spostare nella collezione. |

## reorder(self, index, shapes) {#int-listishape}
Sposta le forme specificate all’interno della collezione di forme, posizionandole a partire dall’indice fornito.

```python
def reorder(self, index, shapes):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L’indice target a base zero dove sarà posizionata la prima forma specificata; <br/><br/> le forme successive seguono nell’ordine fornito. |
| shapes | **List[IShape]** | Una o più istanze di [`IShape`](/slides/python-net/it/aspose.slides/ishape) da spostare nella collezione. |

### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)