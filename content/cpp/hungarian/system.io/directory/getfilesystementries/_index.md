---
title: GetFileSystemEntries()
second_title: Aspose.Slides C++ API hivatkozás
description: Keres a megadott keresési feltételeknek megfelelő fájlok és könyvtárak között, akár a megadott könyvtárban, akár a megadott könyvtárra gyökerező teljes könyvtárfában.
type: docs
weight: 92
url: /hu/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) metódus


Keres a megadott keresési feltételeknek megfelelő fájlok és könyvtárak között, akár a megadott könyvtárban, akár a megadott könyvtárra gyökerező teljes könyvtárfában.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A keresendő könyvtár teljes vagy relatív elérési útja |
| searchPattern | const [String](../../../system/string/)\& | A keresett fájlok és könyvtárak névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak a megadott könyvtárban vagy a megadott könyvtárra gyökerező teljes könyvtárfában kell-e végrehajtani |

### Visszatérési érték

A megtalált fájlok és könyvtárak, amelyek neve megegyezik a **searchPattern**-rel, teljes elérési útjait tartalmazó tömb

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [Directory](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)