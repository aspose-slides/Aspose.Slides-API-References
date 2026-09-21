---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory eigenschap
Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot een hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten.

### Opmerkingen

Deze eigenschap wordt genegeerd als [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) is ingesteld op false, omdat het geheugen dan de enige beschikbare opslaglocatie is en het beperken van het in-geheugen BLOB-gebruik geen effect heeft.

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
* klasse [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)