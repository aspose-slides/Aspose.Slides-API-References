---
title: remove method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Rimuove il layout dalla presentazione.

```python
def remove(self):
    ...
```

### Osservazioni

Per evitare il lancio di PptxEditException controllare la proprietà HasDependingSlides del layout prima.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se il layout è già stato rimosso dalla presentazione o se il layout è utilizzato nella presentazione (la sua <br/>            proprietà HasDependingSlides è true). |

### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)