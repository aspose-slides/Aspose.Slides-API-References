---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání, a to buď ve zvoleném adresáři, nebo v celém stromu adresářů kořeněném v tomto adresáři.
type: docs
weight: 53
url: /cs/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) metoda


Vyhledává soubory a adresáře, které splňují zadaná kritéria hledání, buď ve zadaném adresáři, nebo v celém stromu adresářů kořeněném ve zadaném adresáři.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má hledat |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu souborů a adresářů, které se mají hledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být hledání provedeno pouze ve zadaném adresáři, nebo v celém stromu adresářů kořeněném ve zadaném adresáři |

### Návratová hodnota

Vyčetná kolekce úplných cest nalezených souborů a adresářů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)