---
title: GetDirectories()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledává adresáře, které splňují zadaná kritéria vyhledávání, a to buď ve zvoleném adresáři nebo v celém adresářovém stromu kořeněném ve zvoleném adresáři.
type: docs
weight: 66
url: /cs/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) metoda

Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Úplná nebo relativní cesta k adresáři, ve kterém se má hledat |
| searchPattern | const [String](../../../system/string/)\& | Vzor názvu adresářů, které se mají hledat |
| searchOption | [SearchOption](../../searchoption/) | Určuje, zda má být hledání provedeno pouze ve zvoleném adresáři, nebo v celém adresářovém stromu kořeněném ve zvoleném adresáři |

### Návratová hodnota

Pole úplných cest nalezených adresářů, jejichž názvy odpovídají **searchPattern**

## Viz také

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [Directory](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)