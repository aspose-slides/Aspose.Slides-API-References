---
title: Replace()
second_title: Aspose.Slides für C++ API Referenz
description: Ersetzt den Inhalt einer angegebenen Zieldatei durch die Datei, die vom aktuellen FileInfo-Objekt repräsentiert wird, und erstellt eine Sicherungskopie der ersetzten Datei.
type: docs
weight: 131
url: /de/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) Methode


Ersetzt den Inhalt einer angegebenen Zieldatei durch die Datei, die vom aktuellen [FileInfo](../)-Objekt repräsentiert wird, und erstellt eine Sicherungskopie der ersetzten Datei.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ein Name der zu ersetzenden Datei |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ein Name der Sicherungsdatei |

### Rückgabewert

Ein FileInfor-Objekt, das die Datei bezeichnet, auf die **destinationFileName** verweist

## FileInfo::Replace(const String\&, const String\&, bool) Methode


Ersetzt den Inhalt einer angegebenen Zieldatei durch die Datei, die vom aktuellen [FileInfo](../)-Objekt repräsentiert wird, und erstellt eine Sicherungskopie der ersetzten Datei.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Ein Name der zu ersetzenden Datei |
| destinationBackupFileName | const [String](../../../system/string/)\& | Ein Name der Sicherungsdatei |
| ignoreMetadataErrors | **bool** | Gibt an, ob die Zusammenführungsfehler von der ersetzten Datei zur Ersatzdatei ignoriert werden sollen (true) oder nicht (false) |

### Rückgabewert

Ein FileInfor-Objekt, das die Datei bezeichnet, auf die **destinationFileName** verweist

## Siehe auch

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [FileInfo](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)