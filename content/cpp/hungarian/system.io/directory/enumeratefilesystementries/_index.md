---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides for C++ API Referenciája
description: Keres a megadott könyvtárban vagy a megadott könyvtárban gyökerező teljes könyvtárfában a megadott keresési feltételeknek megfelelő fájlok és könyvtárak után.
type: docs
weight: 53
url: /hu/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) metódus

A megadott keresési feltételeknek megfelelő fájlokat és könyvtárakat keresi meg, akár a megadott könyvtárban, akár a megadott könyvtárban gyökerező teljes könyvtárfában.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A keresendő könyvtár teljes vagy relatív útvonala |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok és könyvtárak névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban kell-e végrehajtani, vagy a megadott könyvtárban gyökerező teljes könyvtárfában |

### Visszatérési érték

A megtalált fájlok és könyvtárak teljes útvonalainak felsorolható gyűjteménye, amelyek neve megfelel a **searchPattern**-nek

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Osztály [String](../../../system/string/)
* Osztály [Directory](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)