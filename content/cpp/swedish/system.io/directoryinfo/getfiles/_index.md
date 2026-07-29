---
title: GetFiles()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array som innehåller delade pekare till FileInfo-objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet.
type: docs
weight: 157
url: /sv/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metod

Returnerar en array som innehåller delade pekare till [FileInfo](../../fileinfo/)-objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metod

Söker efter de filer som uppfyller de angivna sökkriterierna i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filerna att söka efter |

### Returvärde

En array av delade pekare till [FileInfo](../../fileinfo/)-objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) metod

Söker efter de filer som uppfyller de angivna sökkriterierna antingen i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har den katalog som representeras av det aktuella objektet som rot.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den katalog som representeras av det aktuella objektet eller i hela katalogträdet som har den katalog som representeras av det aktuella objektet som rot |

### Returvärde

En array av delade pekare till [FileInfo](../../fileinfo/)-objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klass [DirectoryInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)