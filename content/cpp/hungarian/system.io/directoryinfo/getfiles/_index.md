---
title: GetFiles()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a FileInfo objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat képviselik.
type: docs
weight: 157
url: /hu/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metódus


Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a [FileInfo](../../fileinfo/) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat képviselik.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metódus


Keres a fájlok között, amelyek megfelelnek a megadott keresési kritériumnak az aktuális objektum által képviselt könyvtárban.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok névmintája |

### Visszatérési érték

Egy tömb megosztott mutató a [FileInfo](../../fileinfo/) objektumokra, amelyek a megtalált fájlokat képviselik, és amelyek neve megegyezik a **searchPattern** mintával

## DirectoryInfo::GetFiles(const String\&, SearchOption) metódus


Keres a fájlok között, amelyek megfelelnek a megadott keresési kritériumnak vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtárfában.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresés csak az aktuális objektum által képviselt könyvtárban vagy a teljes, azt gyökérnek tekintő könyvtárfában történjen-e |

### Visszatérési érték

Egy tömb megosztott mutató a [FileInfo](../../fileinfo/) objektumokra, amelyek a megtalált fájlokat képviselik, és amelyek neve megegyezik a **searchPattern** mintával

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Osztály [DirectoryInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)