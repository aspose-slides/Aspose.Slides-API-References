---
title: remove method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Rimuove un layout dalla collezione.

```python
def remove(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | La diapositiva layout da rimuovere dalla collezione. |

### Osservazioni

1) Per evitare il lancio di PptxEditException, verificare prima la proprietà HasDependingSlides del layout.  
2) È possibile utilizzare anche il metodo [`ILayoutSlide.remove`](/slides/python-net/it/aspose.slides/ilayoutslide/remove) per semplificare il codice.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se il layout è utilizzato nella presentazione (la sua proprietà HasDependingSlides è vera). |

### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`LayoutSlideCollection`](/slides/python-net/it/aspose.slides/layoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)