---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy felsorolható gyűjteményt, amely a jelenlegi objektum által képviselt könyvtárban található összes fájlt és könyvtárat tartalmaz.
type: docs
weight: 131
url: /hu/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metódus


Visszaad egy felsorolható gyűjteményt, amely a jelenlegi objektum által képviselt könyvtárban található összes fájlt és könyvtárat tartalmaz.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metódus


Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek a jelenlegi objektum által képviselt könyvtárban.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok és könyvtárak névmintája |

### Visszatérési érték

A megtalált fájlok és könyvtárak [FileSystemInfo](../../filesysteminfo/) objektumaira mutató megosztott mutatók felsorolható gyűjteménye, amelyek neve egyezik a **searchPattern**-lel

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metódus


Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek, akár a jelenlegi objektum által képviselt könyvtárban, akár a teljes könyvtárfa gyökereként a jelenlegi objektum által képviselt könyvtárban.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok és könyvtárak névmintája |
| searchOption | [SearchOption](../../searchoption/) | Meghatározza, hogy a keresés csak a jelenlegi objektum által képviselt könyvtárban vagy a teljes könyvtárfa gyökereként a jelenlegi objektum által képviselt könyvtárban történjen-e |

### Visszatérési érték

A megtalált fájlok és könyvtárak [FileSystemInfo](../../filesysteminfo/) objektumaira mutató megosztott mutatók felsorolható gyűjteménye, amelyek neve egyezik a **searchPattern**-lel

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)