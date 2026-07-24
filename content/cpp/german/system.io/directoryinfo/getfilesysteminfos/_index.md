---
title: GetFileSystemInfos()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array zurück, das gemeinsame Zeiger auf FileSystemInfo-Objekte enthält, die alle Dateien und Verzeichnisse repräsentieren, die im Verzeichnis liegen, das vom aktuellen Objekt repräsentiert wird.
type: docs
weight: 170
url: /de/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() Methode

Gibt ein Array zurück, das gemeinsame Zeiger auf [FileSystemInfo](../../filesysteminfo/)-Objekte enthält, die alle Dateien und Verzeichnisse darstellen, die im Verzeichnis liegen, das vom aktuellen Objekt repräsentiert wird.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) Methode

Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien im vom aktuellen Objekt repräsentierten Verzeichnis erfüllen.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |

### Rückgabewert

Ein Array von gemeinsamen Zeigern auf [FileSystemInfo](../../filesysteminfo/)-Objekte, die die gefundenen Dateien und Verzeichnisse darstellen, deren Namen **searchPattern** entsprechen.

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) Methode

Durchsucht die Dateien und Verzeichnisse, die die angegebenen Suchkriterien entweder im vom aktuellen Objekt repräsentierten Verzeichnis oder im gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis wurzelt, erfüllen.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Das Namensmuster der zu suchenden Dateien und Verzeichnisse |
| searchOption | [SearchOption](../../searchoption/) | Gibt an, ob die Suche nur im vom aktuellen Objekt repräsentierten Verzeichnis oder im gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis wurzelt, durchgeführt werden muss |

### Rückgabewert

Ein Array von gemeinsamen Zeigern auf [FileSystemInfo](../../filesysteminfo/)-Objekte, die die gefundenen Dateien und Verzeichnisse darstellen, deren Namen **searchPattern** entsprechen.

## Siehe auch

* Aufzählung [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)