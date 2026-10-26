---
title: GetDirectories()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array som innehåller delade pekare till DirectoryInfo-objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet.
type: docs
weight: 144
url: /sv/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() metod

Returnerar en array som innehåller delade pekare till [DirectoryInfo](../)-objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) metod

Söker efter katalogerna som uppfyller de angivna sökkriterierna i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för katalogerna att söka efter |

### Returvärde

En array av delade pekare till [DirectoryInfo](../)-objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) metod

Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i den katalog som representeras av det aktuella objektet eller i hela katalogträdet med roten i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för katalogerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen endast ska utföras i den katalog som representeras av det aktuella objektet eller i hela katalogträdet med roten i den katalog som representeras av det aktuella objektet |

### Returvärde

En array av delade pekare till [DirectoryInfo](../)-objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klass [DirectoryInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)