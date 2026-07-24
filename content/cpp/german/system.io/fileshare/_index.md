---
title: FileShare
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, welche Art von Zugriff andere FileStream-Objekte auf eine zu öffnende Datei haben können.
type: docs
weight: 534
url: /de/system.io/fileshare/
---
## FileShare Enum

Gibt an, welche Art von Zugriff andere [FileStream](../filestream/)-Objekte auf eine zu öffnende Datei haben können.

```cpp
enum class FileShare
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Kein Zugriff. |
| Read | 1 | Nur-Lese-Zugriff. |
| Write | 2 | Nur-Schreib-Zugriff. |
| ReadWrite | 3 | Lese- und Schreibzugriff. |
| Delete | 4 | Die Datei kann gelöscht werden. |
| Inheritable | 16 | Macht den Dateihandle für Kindprozesse vererbbar. |

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)