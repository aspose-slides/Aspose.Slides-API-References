---
title: EnumerateDirectories()
second_title: Aspose.Slides für C++ API-Referenz
description: Sucht nach den Verzeichnissen, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, erfüllen.
type: docs
weight: 27
url: /de/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) Methode

Sucht nach den Verzeichnissen, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, erfüllen.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht wird |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### Rückgabewert

Die aufzählbare Sammlung von vollständigen Pfaden der gefundenen Verzeichnisse, deren Namen dem **searchPattern** entsprechen

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)