---
title: GetFiles()
second_title: Aspose.Slides for C++ API-referencia
description: Megkeresi azokat a fájlokat, amelyek megfelelnek a megadott keresési feltételeknek, akár a megadott könyvtárban, akár a megadott könyvtárban gyökerező teljes könyvtárfában.
type: docs
weight: 79
url: /hu/system.io/directory/getfiles/
---
## Directory::GetFiles(const String&, const String&, SearchOption) method

Megkeresi azokat a fájlokat, amelyek megfelelnek a megadott keresési feltételeknek, akár a megadott könyvtárban, akár a megadott könyvtárban gyökerező teljes könyvtárfában.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A keresendő könyvtár teljes vagy relatív elérési útja |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban kell-e elvégezni, vagy a megadott könyvtárban gyökerező teljes könyvtárfában |

### Visszatérési érték

Egy tömb a megtalált fájlok teljes elérési útjairól, amelyek neve megegyezik a **searchPattern**-vel

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)