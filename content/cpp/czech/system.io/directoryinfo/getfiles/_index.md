---
title: GetFiles()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací pole obsahující sdílené ukazatele na objekty FileInfo představující všechny adresáře umístěné v adresáři, který reprezentuje aktuální objekt.
type: docs
weight: 157
url: /cs/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metoda

Vrací pole obsahující sdílené ukazatele na objekty [FileInfo](../../fileinfo/) představující všechny adresáře umístěné v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metoda

Vyhledává soubory, které splňují zadaná kritéria vyhledávání v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů, které se mají hledat |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [FileInfo](../../fileinfo/) představující nalezené soubory, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) metoda

Vyhledává soubory, které splňují zadaná kritéria vyhledávání buď v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů zakořeněném v adresáři reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor souborů, které se mají hledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů zakořeněném v adresáři reprezentovaném aktuálním objektem |

### Návratová hodnota

Pole sdílených ukazatelů na objekty [FileInfo](../../fileinfo/) představující nalezené soubory, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* třída [DirectoryInfo](../)
* třída [String](../../../system/string/)
* jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)