---
title: WriteState
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de status van de XmlWriter.
type: docs
weight: 755
url: /nl/system.xml/writestate/
---
## WriteState enum

Specificeert de status van de [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Start | 0 | Geeft aan dat de XmlWriter::Write-methode nog niet is aangeroepen. |
| Prolog | 1 | Geeft aan dat de proloog wordt geschreven. |
| Element | 2 | Geeft aan dat een element-starttag wordt geschreven. |
| Attribute | 3 | Geeft aan dat een attribuutwaarde wordt geschreven. |
| Content | 4 | Geeft aan dat elementinhoud wordt geschreven. |
| Closed | 5 | Geeft aan dat de [XmlWriter::Close](../xmlwriter/close/) method is aangeroepen. |
| Error | 6 | Er is een uitzondering gegooid, waardoor de [XmlWriter](../xmlwriter/) in een ongeldige toestand is achtergelaten. U kunt de [XmlWriter::Close](../xmlwriter/close/)-methode aanroepen om de [XmlWriter](../xmlwriter/) in de [WriteState::Closed](./)-toestand te plaatsen. Elke andere [XmlWriter](../xmlwriter/)-methodeaanroep resulteert in een InvalidOperationException. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)