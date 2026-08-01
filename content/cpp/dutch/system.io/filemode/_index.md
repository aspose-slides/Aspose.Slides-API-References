---
title: FileMode
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe een bestand moet worden geopend.
type: docs
weight: 508
url: /nl/system.io/filemode/
---
## FileMode enum

Specificeert hoe een bestand moet worden geopend.

```cpp
enum class FileMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| CreateNew | 1 | Create een nieuw bestand. Als het bestand al bestaat, wordt een uitzondering gegooid. |
| Create | 2 | Create een nieuw bestand. Als het bestand al bestaat, wordt het overschreven. |
| Open | 3 | Open een bestaand bestand. Als het bestand niet bestaat, wordt een uitzondering gegooid. |
| OpenOrCreate | 4 | Open een bestaand bestand of creëer een nieuw bestand als het niet bestaat. |
| Truncate | 5 | Open een bestaand bestand en tronkeer het zodat het leeg is. Als het bestand niet bestaat, wordt een uitzondering gegooid. |
| Append | 6 | Open een bestaand bestand en zoek naar het einde ervan of creeer een nieuw bestand als het niet bestaat. |

## Zie ook

* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)