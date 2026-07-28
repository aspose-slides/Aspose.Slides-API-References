---
title: GetDirectories()
second_title: Aspose.Slides C++ API Referencia
description: Keresést végez azokban a könyvtárakban, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megadott könyvtárból kiinduló teljes könyvtárfában.
type: docs
weight: 66
url: /hu/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) metódus

Keresést végez azokban a könyvtárakban, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megadott könyvtárból kiinduló teljes könyvtárfában.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A keresendő könyvtár teljes vagy relatív elérési útja |
| searchPattern | const [String](../../../system/string/)\& | A keresett könyvtárak névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban kell-e végrehajtani, vagy a megadott könyvtárból kiinduló teljes könyvtárfában |

## Visszatérési érték

A megtalált könyvtárak teljes elérési útjait tartalmazó tömb, amelyek neve megegyezik a **searchPattern**-nel

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)