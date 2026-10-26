---
title: interruption_token property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token proprietà
Il token per monitorare le richieste di interruzione.

Questo token gestisce l'intera durata dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). Qualsiasi operazione a lunga durata, come il caricamento o il salvataggio di una presentazione, verrà interrotta chiamando il metodo [`IInterruptionTokenSource.interrupt`](/slides/python-net/it/aspose.slides/iinterruptiontokensource/interrupt) del [`IInterruptionTokenSource`](/slides/python-net/it/aspose.slides/iinterruptiontokensource).

### Definizione:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Vedi anche
* classe [`IInterruptionTokenSource`](/slides/python-net/it/aspose.slides/iinterruptiontokensource)
* classe [`ILoadOptions`](/slides/python-net/it/aspose.slides/iloadoptions)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)