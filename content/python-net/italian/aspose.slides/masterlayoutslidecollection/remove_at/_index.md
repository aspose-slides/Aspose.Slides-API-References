---
title: remove_at method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Rimuove l'elemento all'indice specificato della collezione.


```python
def remove_at(self, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero dell'elemento da rimuovere. |

### Osservazioni

1) Per evitare il lancio di PptxEditException, controlla prima la proprietà HasDependingSlides del layout.
            2) Puoi anche utilizzare il metodo [`ILayoutSlide.remove`](/slides/python-net/it/aspose.slides/ilayoutslide/remove) per semplificare il codice.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se il layout è usato nella presentazione (la sua proprietà HasDependingSlides è true). |



### Vedi anche
* classe [`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)