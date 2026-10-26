---
title: ReadState
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Zustand des Readers an.
type: docs
weight: 703
url: /de/system.xml/readstate/
---
## ReadState Enum

Gibt den Zustand des Readers an.

```cpp
enum class ReadState
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Initial | 0 | Die Methode [XmlReader::Read](../xmlreader/read/) wurde nicht aufgerufen. |
| Interactive | 1 | Die Methode [XmlReader::Read](../xmlreader/read/) wurde aufgerufen. Zusätzliche Methoden können beim Reader aufgerufen werden. |
| Error | 2 | Ein Fehler ist aufgetreten, der das Fortsetzen des Lesevorgangs verhindert. |
| EndOfFile | 3 | Das Ende der Datei wurde erfolgreich erreicht. |
| Closed | 4 | Die Methode [XmlReader::Close](../xmlreader/close/) wurde aufgerufen. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)