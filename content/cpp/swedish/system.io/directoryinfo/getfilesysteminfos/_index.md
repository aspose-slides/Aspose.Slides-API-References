---
title: GetFileSystemInfos()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array som innehåller delade pekare till FileSystemInfo-objekt som representerar alla filer och kataloger som finns i den katalog som det aktuella objektet representerar.
type: docs
weight: 170
url: /sv/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metod

Returnerar en array som innehåller delade pekare till [FileSystemInfo](../../filesysteminfo/)-objekt som representerar alla filer och kataloger som finns i den katalog som det aktuella objektet representerar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metod

Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i den katalog som det aktuella objektet representerar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de filer och kataloger som ska sökas efter |

### Returvärde

En array av delade pekare till [FileSystemInfo](../../filesysteminfo/)-objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metod

Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den katalog som det aktuella objektet representerar eller i hela katalogträdet med rot i den katalog som det aktuella objektet representerar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de filer och kataloger som ska sökas efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med rot i den katalog som det aktuella objektet representerar |

### Returvärde

En array av delade pekare till [FileSystemInfo](../../filesysteminfo/)-objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klass [DirectoryInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)