---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vrací výčtovou kolekci obsahující všechny soubory a adresáře umístěné v adresáři reprezentovaném aktuálním objektem.
type: docs
weight: 131
url: /cs/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metoda


Vrací výčtovou kolekci obsahující všechny soubory a adresáře umístěné v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metoda


Prohledává soubory a adresáře, které splňují zadané kritérium vyhledávání, v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů a adresářů, které se mají vyhledat |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [FileSystemInfo](../../filesysteminfo/), které představují nalezené soubory a adresáře, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metoda


Prohledává soubory a adresáře, které splňují zadané kritérium vyhledávání, buď v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů a adresářů, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda se má vyhledávání provést pouze v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [FileSystemInfo](../../filesysteminfo/), které představují nalezené soubory a adresáře, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [DirectoryInfo](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)