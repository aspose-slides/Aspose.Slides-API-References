---
title: insert_clone method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Inserisce una copia di una diapositiva di layout specificata nella posizione specificata della raccolta.

### Restituisce
Diapositiva inserita.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indice della nuova diapositiva. |
| source_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Diapositiva da clonare. |

### Note
Il nuovo layout sarà collegato alla diapositiva master principale per questa raccolta di layout diapositive.
            Quindi è analogo a copia/incolla con l'opzione "Use Destination Theme" in PowerPoint.

### Vedi anche
* class [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* class [`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)