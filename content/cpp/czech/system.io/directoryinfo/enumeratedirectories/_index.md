---
title: EnumerateDirectories()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací výčtovou kolekci obsahující všechny adresáře umístěné v adresáři reprezentovaném aktuálním objektem.
type: docs
weight: 105
url: /cs/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metoda

Vrací výčtovou kolekci obsahující všechny adresáře umístěné v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metoda

Vyhledá adresáře, které splňují zadaná kritéria vyhledávání v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor adresářů, které se mají vyhledat |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [DirectoryInfo](../) představující nalezené adresáře, jejichž názvy odpovídají **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metoda

Vyhledá adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Názevový vzor adresářů, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze v adresáři reprezentovaném aktuálním objektem, nebo v celém stromu adresářů kořeněném v adresáři reprezentovaném aktuálním objektem |

### Návratová hodnota

Výčtová kolekce sdílených ukazatelů na objekty [DirectoryInfo](../) představující nalezené adresáře, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [DirectoryInfo](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)