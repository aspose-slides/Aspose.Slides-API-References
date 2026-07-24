---
title: GetFileSystemEntries()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien erfüllen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt.
type: docs
weight: 92
url: /de/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) Methode

Durchsucht die Dateien und Verzeichnisse, die den angegebenen Suchkriterien entsprechen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zum zu durchsuchenden Verzeichnis |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt, durchgeführt werden soll |

### Rückgabewert

Ein Array voller Pfade der gefundenen Dateien und Verzeichnisse, deren Namen mit **searchPattern** übereinstimmen

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)