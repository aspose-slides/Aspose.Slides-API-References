---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides voor C++ API Referentie
description: Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen mogen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. Het houden van BLOBs in het geheugen maximaliseert de prestaties maar kan leiden tot een hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of vereisten.
type: docs
weight: 92
url: /nl/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) methode

Definieert de maximale totale omvang (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. BLOB's in het geheugen houden maximaliseert de prestaties maar kan leiden tot een hoog geheugenverbruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of eisen.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Opmerkingen

Deze waarde wordt genegeerd als [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is ingesteld op false, aangezien geheugen dan de enige beschikbare opslaglocatie is en het beperken van het BLOB-gebruik in het geheugen geen effect heeft. 

De standaardwaarde is 629,145,600 bytes (600 MB). 

U kunt deze eigenschap op nul instellen, maar er zal nog steeds een kleine minimale hoeveelheid geheugen gereserveerd worden. 

## Zie ook

* Klasse [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)