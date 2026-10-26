---
title: ReadState
second_title: Aspose.Slides C++ API referencia
description: Meghatározza az olvasó állapotát.
type: docs
weight: 703
url: /hu/system.xml/readstate/
---
## ReadState enum

Meghatározza az olvasó állapotát.

```cpp
enum class ReadState
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Initial | 0 | A [XmlReader::Read](../xmlreader/read/) metódus nem lett meghívva. |
| Interactive | 1 | A [XmlReader::Read](../xmlreader/read/) metódus meghívásra került. További metódusok meghívhatók az olvasón. |
| Error | 2 | Hiba lépett fel, amely megakadályozza a olvasási művelet folytatását. |
| EndOfFile | 3 | A fájl vége sikeresen elérve. |
| Closed | 4 | A [XmlReader::Close](../xmlreader/close/) metódus meghívásra került. |

## See Also

* Névterület [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)