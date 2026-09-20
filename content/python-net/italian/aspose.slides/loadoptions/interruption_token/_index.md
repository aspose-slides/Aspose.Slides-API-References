---
title: interruption_token property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token proprietà
Il token da monitorare per le richieste di interruzione.
            
            Questo token gestisce l'intero ciclo di vita dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio della presentazione, verrà interrotta chiamando il metodo [`InterruptionTokenSource.interrupt`](/slides/python-net/it/aspose.slides/interruptiontokensource/interrupt) del [`InterruptionTokenSource`](/slides/python-net/it/aspose.slides/interruptiontokensource).

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
* classe [`InterruptionTokenSource`](/slides/python-net/it/aspose.slides/interruptiontokensource)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* classe [`LoadOptions`](/slides/python-net/it/aspose.slides/loadoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)