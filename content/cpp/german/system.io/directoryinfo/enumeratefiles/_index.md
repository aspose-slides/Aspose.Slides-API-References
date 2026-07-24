---
title: EnumerateFiles()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine aufzählbare Sammlung zurück, die alle im Verzeichnis des aktuellen Objekts befindlichen Dateien enthält.
type: docs
weight: 118
url: /de/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() Methode

Gibt eine aufzählbare Sammlung zurück, die alle im Verzeichnis befindlichen Dateien enthält, die durch das aktuelle Objekt repräsentiert werden.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) Methode

Durchsucht das Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien |

### Return Value

Die aufzählbare Sammlung von Shared-Pointers zu [FileInfo](../../fileinfo/)-Objekten, die die gefundenen Dateien repräsentieren, deren Namen dem **searchPattern** entsprechen.

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) Methode

Durchsucht das Verzeichnis, das durch das aktuelle Objekt repräsentiert wird, oder den gesamten Verzeichnisbaum, der im Verzeichnis des aktuellen Objekts verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im Verzeichnis des aktuellen Objekts oder im gesamten Verzeichnisbaum, der im Verzeichnis des aktuellen Objekts verwurzelt ist, durchgeführt werden muss |

### Return Value

Die aufzählbare Sammlung von Shared-Pointers zu [FileInfo](../../fileinfo/)-Objekten, die die gefundenen Dateien repräsentieren, deren Namen dem **searchPattern** entsprechen.

## Siehe auch

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)