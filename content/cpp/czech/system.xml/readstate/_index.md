---
title: ReadState
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje stav čtečky.
type: docs
weight: 703
url: /cs/system.xml/readstate/
---
## ReadState enum

Určuje stav čtečky.

```cpp
enum class ReadState
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| Initial | 0 | Metoda [XmlReader::Read](../xmlreader/read/) nebyla zavolána. |
| Interactive | 1 | Metoda [XmlReader::Read](../xmlreader/read/) byla zavolána. Další metody mohou být volány na čtečce. |
| Error | 2 | Došlo k chybě, která zabraňuje pokračování čtení. |
| EndOfFile | 3 | Konec souboru byl úspěšně dosažen. |
| Closed | 4 | Metoda [XmlReader::Close](../xmlreader/close/) byla zavolána. |

## Viz také

* jmenný prostor [System::Xml](../)
* knihovna [Aspose.Slides](../../)