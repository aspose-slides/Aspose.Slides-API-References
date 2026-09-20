---
title: presentation_locking_behavior property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## proprietà presentation_locking_behavior
Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria dell'origine - file 
            o flusso durante la durata dell'istanza. Se l'istanza è proprietaria, blocca l'origine. Questo aiuta 
            a migliorare il consumo di memoria e le prestazioni durante il lavoro con BLOB, ma l'origine (flusso o file) 
            non può essere modificata durante la durata dell'istanza di Presentation. Questo è un esempio:

### Definizione:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Vedi anche
* classe [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)