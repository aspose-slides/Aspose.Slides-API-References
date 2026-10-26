---
title: EnumerateFiles()
second_title: Aspose.Slides C++ API referencia
description: Keresés a megadott keresési kritériumoknak megfelelő fájlokra, akár a megadott könyvtárban, akár a megadott könyvtárra gyökerező teljes könyvtárfában.
type: docs
weight: 40
url: /hu/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) metódus


Megkeresi azokat a fájlokat, amelyek megfelelnek a megadott keresési feltételeknek, akár a megadott könyvtárban, akár a megadott könyvtárra gyökerező teljes könyvtárfában.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Teljes vagy relatív útvonal a keresendő könyvtárhoz |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok névemintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban vagy a megadott könyvtárra gyökerező teljes könyvtárfában kell-e végrehajtani |

### Visszatérési érték

A megtalált fájlok teljes útvonalainak felsorolható gyűjteménye, amelyek neve megegyezik a **searchPattern** mintával

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Osztály [String](../../../system/string/)
* Osztály [Directory](../)
* névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)