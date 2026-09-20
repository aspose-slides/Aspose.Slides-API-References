---
title: remove method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Rimuove un layout dalla raccolta.


```python
def remove(self, value):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | La diapositiva di layout da rimuovere dalla raccolta. |

### Osservazioni

1) Per evitare il lancio di PptxEditException controllare la proprietà HasDependingSlides del layout prima.
2) È inoltre possibile utilizzare il metodo [`ILayoutSlide.remove`](/slides/python-net/it/aspose.slides/ilayoutslide/remove) per semplificare il codice.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se il layout è utilizzato nella presentazione (la sua proprietà HasDependingSlides è true). |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`ILayoutSlideCollection`](/slides/python-net/it/aspose.slides/ilayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)