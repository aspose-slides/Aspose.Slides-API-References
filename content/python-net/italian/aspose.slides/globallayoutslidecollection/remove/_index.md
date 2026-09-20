---
title: remove method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Rimuove un layout dalla collezione.

```python
def remove(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Il layout slide da rimuovere dalla collezione. |

### Osservazioni

1) Per evitare il lancio di PptxEditException, controllare prima la proprietà HasDependingSlides del layout.
2) Puoi usare anche il metodo [`ILayoutSlide.remove`](/slides/python-net/it/aspose.slides/ilayoutslide/remove) per semplificare il codice.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Lanciata se il layout è utilizzato nella presentazione (la sua proprietà HasDependingSlides è vera). |

### Vedi anche
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)