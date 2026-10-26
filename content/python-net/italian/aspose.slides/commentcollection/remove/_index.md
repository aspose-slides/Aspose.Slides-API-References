---
title: remove method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
Rimuove la prima occorrenza del comment specificato in una collezione.

```python
def remove(self, comment):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/it/aspose.slides/icomment) | Il comment da rimuovere da una collezione. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Se comment è `None` |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se comment è già stato rimosso. |

### Vedi anche
* classe [`CommentCollection`](/slides/python-net/it/aspose.slides/commentcollection)
* classe [`IComment`](/slides/python-net/it/aspose.slides/icomment)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)