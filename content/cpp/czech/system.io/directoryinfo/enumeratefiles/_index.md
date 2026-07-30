---
title: EnumerateFiles()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací výčtovou kolekci obsahující všechny soubory umístěné v adresáři představovaném aktuálním objektem.
type: docs
weight: 118
url: /cs/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metoda


Vrací výčtovou kolekci obsahující všechny soubory umístěné v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metoda


Vyhledává soubory, které splňují zadaná kritéria vyhledávání v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu souborů, které mají být vyhledány |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [FileInfo](../../fileinfo/) představující nalezené soubory, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metoda


Vyhledává soubory, které splňují zadaná kritéria vyhledávání buď v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu souborů, které mají být vyhledány |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [FileInfo](../../fileinfo/) představující nalezené soubory, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)