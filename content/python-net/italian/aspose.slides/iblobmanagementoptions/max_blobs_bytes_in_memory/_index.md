---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory proprietà
Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato consumo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.

### Osservazioni
Questa proprietà è ignorata se [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) è impostato su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha alcun effetto.

### Definizione:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Vedi anche
* classe [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)