---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Datei (oder überschreibt eine vorhandene) und öffnet sie zum Lese- und Schreibzugriff unter Verwendung der angegebenen Puffergröße und Optionen.
type: docs
weight: 53
url: /de/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method

Erstellt eine neue Datei (oder überschreibt eine vorhandene) und öffnet sie für Lese- und Schreibzugriff unter Verwendung der angegebenen Puffergröße und Optionen.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu erstellenden oder zu überschreibenden Datei |
| bufferSize | **int32_t** | Die Anzahl der Bytes, die beim Lesen aus und Schreiben in die Datei gepuffert werden |
| options | [FileOptions](../../fileoptions/) | Gibt an, wie die Datei erstellt oder überschrieben wird |

### Return Value

Ein Shared-Pointer auf das [FileStream](../../filestream/)-Objekt, das mit der angegebenen Datei verknüpft ist

## Siehe auch

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)