---
title: GetFiles()
second_title: Aspose.Slides für C++ API Referenz
description: Sucht nach den Dateien, die den angegebenen Suchkriterien entsprechen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt.
type: docs
weight: 79
url: /de/system.io/directory/getfiles/
---
## Directory::GetFiles(const String&, const String&, SearchOption) Methode

Durchsucht die Dateien, die den angegebenen Suchkriterien entsprechen, entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht werden soll |
| searchPattern | const [String](../../../system/string/)\& | Namensmuster der zu suchenden Dateien |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis wurzelt, durchgeführt werden muss |

### Rückgabewert

Ein Array voller Pfade der gefundenen Dateien, deren Namen mit **searchPattern** übereinstimmen

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)