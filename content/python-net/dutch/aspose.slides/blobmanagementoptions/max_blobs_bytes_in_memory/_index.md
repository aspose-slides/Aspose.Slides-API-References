---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory eigenschap
Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs geladen in het geheugen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen.

### Opmerkingen
Deze eigenschap wordt genegeerd als [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) op false is ingesteld, aangezien het geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft.

### Definitie:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Zie ook
* klasse [`BlobManagementOptions`](/slides/python-net/nl/aspose.slides/blobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)