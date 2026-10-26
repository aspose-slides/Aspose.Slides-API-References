---
title: insert_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Inserisce una copia di una diapositiva layout specificata nella posizione indicata della collezione.

### Restituisce
Diapositiva inserita.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova diapositiva. |
| source_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Diapositiva da clonare. |

### Osservazioni
Il nuovo layout sarà collegato alla diapositiva master principale per questa collezione di diapositive layout.  
Quindi è l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint.

### Vedi anche
* class [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* class [`IMasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)