---
title: EnumerateDirectories()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledá adresáře, které splňují zadaná kritéria hledání, a to buď ve specifikovaném adresáři nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři.
type: docs
weight: 27
url: /cs/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) metoda

Vyhledává adresáře, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má hledat |
| searchPattern | const [String](../../../system/string/)\& | Vzorek názvu adresářů, které se mají hledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být hledání provedeno pouze ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři |

### Návratová hodnota

Iterovatelná kolekce úplných cest nalezených adresářů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Třída [String](../../../system/string/)
* Třída [Directory](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)