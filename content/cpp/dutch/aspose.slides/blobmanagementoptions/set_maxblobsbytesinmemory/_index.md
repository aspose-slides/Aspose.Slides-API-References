---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen kunnen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugengebruik. Gebruik deze eigenschap om het gedrag aan uw omgeving of eisen aan te passen.
type: docs
weight: 92
url: /nl/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) methode

Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) gebruikt. BLOBs in het geheugen houden maximaliseert de prestaties maar kan leiden tot hoog geheugengebruik. Gebruik deze eigenschap om het gedrag aan uw omgeving of vereisten aan te passen.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Opmerkingen

Deze waarde wordt genegeerd als [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is ingesteld op false, omdat geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-memory BLOB-gebruik geen effect heeft. 

De standaardwaarde is 629,145,600 bytes (600 MB). 

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd. 
## Zie ook

* Klasse [BlobManagementOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)