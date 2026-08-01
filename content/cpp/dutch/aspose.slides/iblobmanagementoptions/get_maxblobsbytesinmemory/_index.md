---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen kunnen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas zodra deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. Het in het geheugen houden van BLOBs maximaliseert de prestaties, maar kan leiden tot een hoog geheugengebruik. Gebruik deze eigenschap om het gedrag af te stemmen op uw omgeving of vereisten.
type: docs
weight: 79
url: /nl/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() methode

Definieert de maximale totale grootte (in bytes) die alle BLOBs in het geheugen kunnen innemen. Standaard worden alle BLOBs in het geheugen geladen; pas zodra deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) toegepast. Het bewaren van BLOBs in het geheugen maximaliseert de prestaties, maar kan leiden tot een hoog geheugengebruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of eisen.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Opmerkingen

Deze waarde wordt genegeerd als [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) op false is ingesteld, aangezien het geheugen dan de enige beschikbare opslaglocatie is en het beperken van in-geheugen BLOB-gebruik geen effect heeft. 

De standaardwaarde is 629,145,600 bytes (600 MB). 

U kunt deze eigenschap op nul instellen, maar er wordt nog steeds een kleine minimale hoeveelheid geheugen gereserveerd. 

## Zie ook

* Klasse [IBlobManagementOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)