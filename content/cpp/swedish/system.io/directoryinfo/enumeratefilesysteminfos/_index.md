---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i den katalog som representeras av det aktuella objektet.
type: docs
weight: 131
url: /sv/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metod

Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metod

Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i den katalog som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de filer och kataloger som ska sökas efter |

### Returvärde

Den enumererbara samlingen av delade pekare till [FileSystemInfo](../../filesysteminfo/)-objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metod

Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i den katalog som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de filer och kataloger som ska sökas efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i den katalog som representeras av det aktuella objektet |

### Returvärde

Den enumererbara samlingen av delade pekare till [FileSystemInfo](../../filesysteminfo/)-objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se också

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)