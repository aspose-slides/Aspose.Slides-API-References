---
title: max_blobs_bytes_in_memory property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory proprietà
Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB
            vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un utilizzo elevato della memoria. Usa
            questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.


### Remarks
Questa proprietà viene ignorata se [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/it/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) è impostato su false, poiché la memoria è allora
            l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### See Also
* class [`BlobManagementOptions`](/slides/python-net/it/aspose.slides/blobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)