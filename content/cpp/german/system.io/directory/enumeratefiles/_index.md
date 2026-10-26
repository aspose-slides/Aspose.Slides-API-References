---
title: EnumerateFiles()
second_title: Aspose.Slides für C++ API-Referenz
description: Sucht nach den Dateien, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, erfüllen.
type: docs
weight: 40
url: /de/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) Methode

Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zu dem Verzeichnis, in dem gesucht werden soll |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### Rückgabewert

Die aufzählbare Sammlung voller Pfade der gefundenen Dateien, deren Namen mit **searchPattern** übereinstimmen

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)