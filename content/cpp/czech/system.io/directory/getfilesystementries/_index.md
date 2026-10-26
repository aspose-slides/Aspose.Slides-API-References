---
title: GetFileSystemEntries()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání, a to buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři.
type: docs
weight: 92
url: /cs/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) metoda


Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání, buď v určeném adresáři, nebo v celém stromu adresářů kořeněném v určeném adresáři.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má vyhledávat |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu souborů a adresářů, které se mají vyhledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být vyhledávání provedeno pouze ve specifikovaném adresáři nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři |

### Návratová hodnota

Pole úplných cest nalezených souborů a adresářů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)