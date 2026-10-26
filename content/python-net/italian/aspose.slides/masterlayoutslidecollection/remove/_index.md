---
title: remove method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Rimuove un layout dalla raccolta.

```python
def remove(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Il layout slide da rimuovere dalla raccolta. |

### Osservazioni

1) Per evitare il lancio di PptxEditException, controllare prima la proprietà HasDependingSlides del layout.  
2) È possibile utilizzare anche il metodo [`ILayoutSlide.remove`](/slides/python-net/it/aspose.slides/ilayoutslide/remove) per semplificare il codice.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Lanciata se il layout è usato nella presentazione (la sua proprietà HasDependingSlides è true). |

### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)