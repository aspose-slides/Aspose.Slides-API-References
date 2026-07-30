---
title: GetFileSystemInfos()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací pole obsahující sdílené ukazatele na objekty FileSystemInfo představující všechny soubory a adresáře umístěné v adresáři reprezentovaném aktuálním objektem.
type: docs
weight: 170
url: /cs/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metoda

Vrací pole obsahující sdílené ukazatele na objekty [FileSystemInfo](../../filesysteminfo/) představující všechny soubory a adresáře umístěné v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metoda

Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů a adresářů, které se mají vyhledat |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [FileSystemInfo](../../filesysteminfo/) představující nalezené soubory a adresáře, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metoda

Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů a adresářů, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [FileSystemInfo](../../filesysteminfo/) představující nalezené soubory a adresáře, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Třída [DirectoryInfo](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)