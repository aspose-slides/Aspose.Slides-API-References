---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. Het behouden van BLOB's in het geheugen maximaliseert de prestaties maar kan leiden tot een hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten.
type: docs
weight: 79
url: /nl/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() methode


Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. Het behouden van BLOB's in het geheugen maximaliseert de prestaties maar kan leiden tot een hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Opmerkingen


Deze waarde wordt genegeerd als [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) op false is ingesteld, omdat geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-geheugen BLOB-gebruik geen effect heeft. 

De standaardwaarde is 629.145.600 bytes (600 MB). 

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd. 
## Zie ook

* Klasse [BlobManagementOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)