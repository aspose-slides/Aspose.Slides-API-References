---
title: NewLineHandling
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe regeleinden moeten worden verwerkt.
type: docs
weight: 690
url: /nl/system.xml/newlinehandling/
---
## NewLineHandling enum

Specificeert hoe regeleinden moeten worden verwerkt.

```cpp
enum class NewLineHandling
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Replace | 0 | Regeleinde-tekens worden vervangen om overeen te komen met het teken dat is gespecificeerd in de [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/)-waarde. |
| Entitize | 1 | Regeleinde-tekens worden ge-entitiseerd. Deze instelling behoudt alle tekens wanneer de uitvoer wordt gelezen door een normaliserende [XmlReader](../xmlreader/). |
| None | 2 | De regeleinde-tekens blijven ongewijzigd. De uitvoer is hetzelfde als de invoer. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)