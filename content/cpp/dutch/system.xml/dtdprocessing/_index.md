---
title: DtdProcessing
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de opties voor het verwerken van DTD's. De DtdProcessing-enumeratie wordt gebruikt door de XmlReaderSettings klasse.
type: docs
weight: 638
url: /nl/system.xml/dtdprocessing/
---
## DtdProcessing enum

Specificeert de opties voor het verwerken van DTD's. De DtdProcessing-enumeratie wordt gebruikt door de [XmlReaderSettings](../xmlreadersettings/) klasse.

```cpp
enum class DtdProcessing
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Prohibit | 0 | Specificeert dat wanneer een DTD wordt aangetroffen, een XmlException wordt gegooid met een bericht dat aangeeft dat DTD's verboden zijn. Dit is het standaardgedrag. |
| Ignore | 1 | Veroorzaakt dat het DOCTYPE-element wordt genegeerd. Er vindt geen DTD-verwerking plaats, en de DTD/DOCTYPE gaat verloren bij de uitvoer. |
| Parse | 2 | Wordt gebruikt voor het parseren van DTD's. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)