---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory Eigenschaft
Definiert die maximale Gesamtegröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs
            in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre
            Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.


### Hinweise

Diese Eigenschaft wird ignoriert, wenn [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) auf false gesetzt ist, da der Speicher dann der einzige verfügbare Speicherort ist und das Begrenzen der in-Speicher-BLOB-Nutzung keine Wirkung hat.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Siehe auch
* Klasse [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)