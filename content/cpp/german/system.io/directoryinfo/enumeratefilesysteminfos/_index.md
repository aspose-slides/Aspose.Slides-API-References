---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine aufzählbare Sammlung zurück, die alle Dateien und Verzeichnisse enthält, die im vom aktuellen Objekt repräsentierten Verzeichnis liegen.
type: docs
weight: 131
url: /de/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() Methode

Gibt eine aufzählbare Sammlung zurück, die alle Dateien und Verzeichnisse enthält, die im vom aktuellen Objekt repräsentierten Verzeichnis liegen.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) Methode

Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |

### Rückgabewert

Die aufzählbare Sammlung von Shared-pointer-Objekten zu [FileSystemInfo](../../filesysteminfo/)-Objekten, die die gefundenen Dateien und Verzeichnisse darstellen, deren Namen **searchPattern** entsprechen

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) Methode

Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im vom aktuellen Objekt repräsentierten Verzeichnis oder im gesamten Verzeichnisbaum, der darin verwurzelt ist, durchgeführt werden soll |

### Rückgabewert

Die aufzählbare Sammlung von Shared-pointer-Objekten zu [FileSystemInfo](../../filesysteminfo/)-Objekten, die die gefundenen Dateien und Verzeichnisse darstellen, deren Namen **searchPattern** entsprechen

## Siehe auch

* Aufzählung [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)