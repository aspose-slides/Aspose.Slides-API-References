---
title: GetDirectories()
second_title: Aspose.Slides für C++ API Referenz
description: Durchsucht die Verzeichnisse, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, erfüllen.
type: docs
weight: 66
url: /de/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String&, const String&, SearchOption) Methode

Durchsucht die Verzeichnisse, die die angegebenen Suchkriterien entweder im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, erfüllen.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Vollständiger oder relativer Pfad zum Verzeichnis, in dem gesucht werden soll |
| searchPattern | const [String](../../../system/string/)\& | Namensmuster der zu suchenden Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im angegebenen Verzeichnis oder im gesamten Verzeichnisbaum, der im angegebenen Verzeichnis verwurzelt ist, durchgeführt werden soll |

### Rückgabewert

Ein Array mit den vollständigen Pfaden der gefundenen Verzeichnisse, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)