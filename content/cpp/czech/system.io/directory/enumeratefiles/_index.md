---
title: EnumerateFiles()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledává soubory, které splňují zadaná kritéria vyhledávání, a to buď ve specifikovaném adresáři, nebo v celém stromu adresářů, který má jako kořen specifikovaný adresář.
type: docs
weight: 40
url: /cs/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) metoda

Vyhledává soubory, které splňují zadaná kritéria vyhledávání, a to buď ve specifikovaném adresáři, nebo v celém stromu adresářů, který začíná ve specifikovaném adresáři.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má hledat |
| searchPattern | const [String](../../../system/string/)\& | Šablona názvu souborů, které se mají hledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda se hledání má provádět pouze ve specifikovaném adresáři, nebo v celém stromu adresářů, který začíná ve specifikovaném adresáři |

### Návratová hodnota

Výčtová kolekce úplných cest nalezených souborů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Výčet [SearchOption](../../searchoption/)
* Definice typu [StringEnumerablePtr](../stringenumerableptr/)
* Třída [String](../../../system/string/)
* Třída [Directory](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)