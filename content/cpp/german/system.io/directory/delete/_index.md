---
title: Delete()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt die angegebene Datei oder das Verzeichnis. Wirft keine Ausnahme.
type: docs
weight: 14
url: /de/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) Methode

Entfernt die angegebene Datei oder das Verzeichnis. Wirft keine Ausnahme.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad zum Verzeichnis oder zur Datei, die entfernt werden soll |
| recursive | **bool** | Wenn **path** ein nicht leeres Verzeichnis angibt, bestimmt **recursive**, ob der gesamte Inhalt des Verzeichnisses rekursiv entfernt werden soll; ist das durch **path** angegebene Verzeichnis nicht leer und **recursive** ist 'false', schlägt die Operation fehl |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)