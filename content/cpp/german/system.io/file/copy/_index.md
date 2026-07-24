---
title: Copy()
second_title: Aspose.Slides für C++ API-Referenz
description: Kopiert die angegebene Datei an den angegebenen Speicherort. Falls die Zieldatei bereits existiert, gibt ein Parameter an, ob sie überschrieben werden soll.
type: docs
weight: 40
url: /de/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) Methode

Kopiert die angegebene Datei an den angegebenen Ort. Falls die Zieldatei bereits existiert, gibt ein Parameter an, ob sie überschrieben werden soll.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Ein Pfad der zu kopierenden Datei |
| destFileName | const [String](../../../system/string/)\& | Ein Pfad des neuen Speicherorts der zu kopierenden Datei |
| overwrite | **bool** | True, wenn die vorhandene Zieldatei überschrieben werden soll, false, wenn das Kopieren fehlschlagen soll, falls die Zieldatei bereits existiert |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)