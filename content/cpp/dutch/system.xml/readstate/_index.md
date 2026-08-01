---
title: ReadState
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de status van de lezer.
type: docs
weight: 703
url: /nl/system.xml/readstate/
---
## ReadState enum


Specificeert de status van de lezer.

```cpp
enum class ReadState
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Initial | 0 | De [XmlReader::Read](../xmlreader/read/) methode is niet aangeroepen. |
| Interactive | 1 | De [XmlReader::Read](../xmlreader/read/) methode is aangeroepen. Extra methoden kunnen op de lezer worden aangeroepen. |
| Error | 2 | Er is een fout opgetreden die de leesbewerking verhindert om door te gaan. |
| EndOfFile | 3 | Het einde van het bestand is met succes bereikt. |
| Closed | 4 | De [XmlReader::Close](../xmlreader/close/) methode is aangeroepen. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)