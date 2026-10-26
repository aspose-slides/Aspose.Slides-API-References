---
title: FileOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft geavanceerde opties weer voor het maken van een FileStream-object.
type: docs
weight: 521
url: /nl/system.io/fileoptions/
---
## FileOptions enum

Geeft geavanceerde opties weer voor het maken van een [FileStream](../filestream/) object.

```cpp
enum class FileOptions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Geen extra opties. |
| Encrypted | 16384 | Het bestand is versleuteld. NIET GEREALISEERD. |
| DeleteOnClose | 67108864 | Het bestand moet automatisch worden verwijderd wanneer het niet meer in gebruik is. |
| SequentialScan | 134217728 | Het bestand moet sequentieel worden benaderd. |
| RandomAccess | 268435456 | Het bestand wordt willekeurig benaderd. |
| Asynchronous | 1073741824 | Het bestand kan worden gebruikt voor asynchrone I/O-bewerkingen. |
| WriteThrough | n/a | Alle schrijfbewerkingen moeten rechtstreeks naar de schijf gaan, waarbij eventuele tussenliggende cache wordt omzeild. |

## Zie ook

* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)