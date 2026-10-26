---
title: Replace()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt den Inhalt einer Datei durch eine andere und erstellt eine Sicherungskopie der ersetzten Datei.
type: docs
weight: 339
url: /de/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) Methode


Ersetzt den Inhalt einer Datei durch eine andere und erstellt eine Sicherungskopie der ersetzten Datei.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Ein Name der Datei, mit der ersetzt werden soll |
| destinationFileName | const [String](../../../system/string/)\& | Ein Name der zu ersetzenden Datei |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ein Name der Sicherungsdatei |
| ignoreMetadataErrors | **bool** | Gibt an, ob die Merge-Fehler von der ersetzten Datei zur Ersatzdatei ignoriert werden sollen (true) oder nicht (false) |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)