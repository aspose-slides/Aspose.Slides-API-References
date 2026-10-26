---
title: GetFiles()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledá soubory, které splňují zadaná kritéria vyhledávání, buď ve zvoleném adresáři, nebo v celém stromu adresářů kořeněném v tomto adresáři.
type: docs
weight: 79
url: /cs/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) metoda


Vyhledá soubory, které splňují zadaná kritéria vyhledávání, buď ve zvoleném adresáři, nebo v celém stromu adresářů kořeněném v tomto adresáři.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má vyhledávat |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu souborů, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno jen ve zvoleném adresáři, nebo v celém stromu adresářů kořeněném v tomto adresáři |

### Návratová hodnota

Pole úplných cest nalezených souborů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Výčet [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [Directory](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)