---
title: EnumerateFiles()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en uppräkningsbar samling som innehåller alla filer som finns i katalogen som representeras av det aktuella objektet.
type: docs
weight: 118
url: /sv/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metod

Returnerar en uppräkningsbar samling som innehåller alla filer som finns i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metod

Söker efter filer som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filerna som ska sökas efter |

### Returvärde

Den uppräkningsbara samlingen av delade pekare till [FileInfo](../../fileinfo/)-objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metod

Söker efter filer som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filerna som ska sökas efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen bara ska utföras i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet |

### Returvärde

Den uppräkningsbara samlingen av delade pekare till [FileInfo](../../fileinfo/)-objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)