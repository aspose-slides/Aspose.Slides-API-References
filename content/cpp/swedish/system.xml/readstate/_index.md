---
title: ReadState
second_title: Aspose.Slides för C++ API-referens
description: Specificerar läsarens tillstånd.
type: docs
weight: 703
url: /sv/system.xml/readstate/
---
## ReadState enum

Specificerar läsarens tillstånd.

```cpp
enum class ReadState
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Initial | 0 | Metoden [XmlReader::Read](../xmlreader/read/) har inte anropats. |
| Interactive | 1 | Metoden [XmlReader::Read](../xmlreader/read/) har anropats. Ytterligare metoder kan anropas på läsaren. |
| Error | 2 | Ett fel inträffade som förhindrar att läsoperationen fortsätter. |
| EndOfFile | 3 | Slutet på filen har nåtts framgångsrikt. |
| Closed | 4 | Metoden [XmlReader::Close](../xmlreader/close/) har anropats. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)