---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchsucht die Dateien und Verzeichnisse, die den angegebenen Suchkriterien entsprechen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist.
type: docs
weight: 53
url: /de/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) Methode

Durchsucht die Dateien und Verzeichnisse, die den angegebenen Suchkriterien entsprechen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht werden soll |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### Rückgabewert

Die aufzählbare Sammlung vollständiger Pfade der gefundenen Dateien und Verzeichnisse, deren Namen **searchPattern** entsprechen

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)