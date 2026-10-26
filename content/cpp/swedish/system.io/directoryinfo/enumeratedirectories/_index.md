---
title: EnumerateDirectories()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en enumererbar samling som innehåller alla kataloger som finns i den katalog som representeras av det aktuella objektet.
type: docs
weight: 105
url: /sv/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metod


Returnerar en enumererbar samling som innehåller alla kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metod


Söker efter de kataloger som uppfyller det angivna sökkriteriet i den katalog som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de kataloger som ska sökas efter |

### Returvärde

Den enumererbara samlingen av delade pekare till [DirectoryInfo](../)-objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metod


Söker efter de kataloger som uppfyller det angivna sökkriteriet antingen i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har den katalogen som rot.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för de kataloger som ska sökas efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har den katalogen som rot |

### Returvärde

Den enumererbara samlingen av delade pekare till [DirectoryInfo](../)-objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [DirectoryInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)