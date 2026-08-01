---
title: Zip64Mode
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert wanneer ZIP64-formaatextensies moeten worden gebruikt voor een OpenXML-bestand.
type: docs
weight: 1119
url: /nl/aspose.slides.export/zip64mode/
---
## Zip64Mode enum


Geeft aan wanneer ZIP64-formaatextensies moeten worden gebruikt voor een OpenXML-bestand.

```cpp
enum class Zip64Mode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Never | 0 | Gebruik geen ZIP64-formaatextensies. |
| IfNecessary | 1 | Gebruik ZIP64-formaatextensies indien nodig. |
| Always | 2 | Gebruik altijd ZIP64-formaatextensies. |

## Opmerkingen


Een OpenXML-bestand is een ZIP-archief dat een limiet van 4 GB (2^32 bytes) heeft voor de ongecomprimeerde grootte van een bestand, de gecomprimeerde grootte van een bestand en de totale grootte van het archief, evenals een limiet van 65 535 (2^16-1) bestanden in het archief. ZIP64-formaatextensies verhogen de limieten tot 2^64. 
## Zie ook

* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)