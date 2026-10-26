---
title: CopyTo()
second_title: Aspose.Slides für C++ API Referenz
description: Kopiert die vom aktuellen Objekt repräsentierte Datei an den angegebenen Speicherort. Wenn die Zieldatei bereits existiert, schlägt das Kopieren fehl.
type: docs
weight: 105
url: /de/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) Methode

Kopiert die vom aktuellen Objekt repräsentierte Datei an den angegebenen Speicherort. Wenn die Zieldatei bereits existiert, schlägt das Kopieren fehl.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Der Name der Zieldatei |

### Rückgabewert

Ein [FileInfo](../) Objekt, das die Kopie repräsentiert

## FileInfo::CopyTo(const String\&, bool) Methode

Kopiert die vom aktuellen Objekt repräsentierte Datei an den angegebenen Speicherort. Ein Parameter gibt an, ob die vorhandene Zieldatei überschrieben werden soll.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Der Name der Zieldatei |
| overwrite | **bool** | True wenn die vorhandene Zieldatei überschrieben werden soll, false wenn das Kopieren fehlschlagen soll, falls die Zieldatei bereits existiert |

### Rückgabewert

Ein [FileInfo](../) Objekt, das die Kopie repräsentiert

## Siehe auch

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [FileInfo](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)