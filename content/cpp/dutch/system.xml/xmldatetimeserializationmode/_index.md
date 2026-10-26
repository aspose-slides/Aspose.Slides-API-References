---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe de tijdwaarde behandeld moet worden bij het converteren tussen een string en DateTime.
type: docs
weight: 781
url: /nl/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Specificeert hoe de tijdwaarde behandeld moet worden bij het converteren tussen string en [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Values

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Local | 0 | Behandel als lokale tijd. Als het [DateTime](../../system/datetime/) object een Coordinated Universal Time (UTC) vertegenwoordigt, wordt het geconverteerd naar de lokale tijd. |
| Utc | 1 | Behandel als een UTC. Als het [DateTime](../../system/datetime/) object een lokale tijd vertegenwoordigt, wordt het geconverteerd naar een UTC. |
| Unspecified | 2 | Behandel als lokale tijd als een [DateTime](../../system/datetime/) wordt geconverteerd naar een string. Als een string wordt geconverteerd naar [DateTime](../../system/datetime/), converteer dan naar lokale tijd als er een tijdzone is opgegeven. |
| RoundtripKind | 3 | Tijdzone-informatie moet behouden blijven bij het converteren. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)