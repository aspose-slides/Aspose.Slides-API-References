---
title: GetDirectories()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací pole obsahující sdílené ukazatele na objekty DirectoryInfo představující všechny složky umístěné ve složce reprezentované aktuálním objektem.
type: docs
weight: 144
url: /cs/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method


Vrací pole obsahující sdílené ukazatele na objekty [DirectoryInfo](../) představující všechny složky umístěné ve složce reprezentované aktuálním objektem.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) method


Vyhledává složky, které splňují zadaná kritéria vyhledávání, ve složce reprezentované aktuálním objektem.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu složek, které se mají vyhledat |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [DirectoryInfo](../) představující nalezené složky, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) method


Vyhledává složky, které splňují zadaná kritéria vyhledávání, buď ve složce reprezentované aktuálním objektem, nebo v celém stromu složek kořeněném ve složce reprezentované aktuálním objektem.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu složek, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze ve složce reprezentované aktuálním objektem, nebo v celém stromu složek kořeněném ve složce reprezentované aktuálním objektem |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [DirectoryInfo](../) představující nalezené složky, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)