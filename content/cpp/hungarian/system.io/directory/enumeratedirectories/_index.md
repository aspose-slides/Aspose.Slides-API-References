---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API referenciája
description: Keres a megadott keresési feltételeket kielégítő könyvtárak között, akár a megadott könyvtárban, akár a megadott könyvtárban gyökerező teljes könyvtárfában.
type: docs
weight: 27
url: /hu/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) módszer


Keres a megadott keresési feltételeket kielégítő könyvtárak között, akár a megadott könyvtárban, akár a megadott könyvtárban gyökerező teljes könyvtárfában.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Teljes vagy relatív útvonal a keresendő könyvtárhoz |
| searchPattern | const [String](../../../system/string/)& | A keresendő könyvtárak névformája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban kell-e végrehajtani, vagy a megadott könyvtárban gyökerező teljes könyvtárfában |

### Return Value

Az megtalált könyvtárak teljes útvonalainak felsorolható gyűjteménye, amelyek neve megegyezik a **searchPattern**-nel

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Osztály [String](../../../system/string/)
* Osztály [Directory](../)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)