---
title: reorder method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme.

```python
def reorder(self, index, shape):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice di destinazione base zero dove verrà collocata la forma. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da spostare all'interno della raccolta. |

## reorder(self, index, shapes) {#int-listishape}
Sposta le forme specificate all'interno della raccolta di forme, posizionandole a partire dall'indice fornito.

```python
def reorder(self, index, shapes):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice di destinazione base zero dove verrà collocata la prima forma specificata; <br/><br/>            le forme successive seguiranno nell'ordine fornito. |
| shapes | **List[IShape]** | Una o più istanze di [`IShape`](/slides/python-net/it/aspose.slides/ishape) da spostare all'interno della raccolta. |

### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)