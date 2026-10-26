---
title: presentation_locking_behavior property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior proprietà
Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente – file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation.

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
* classe [`BlobManagementOptions`](/slides/python-net/it/aspose.slides/blobmanagementoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)