---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaad egy enumerálható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes fájlt.
type: docs
weight: 118
url: /hu/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metódus

Visszaad egy enumerálható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes fájlt.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metódus

Kikeresi azokat a fájlokat, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresett fájlok néveménye |

### Visszatérési érték

Az enumerálható gyűjtemény, amely [FileInfo](../../fileinfo/) objektumokra mutató megosztott pointereket tartalmaz, a megtalált fájlokat reprezentálja, melyek neve **searchPattern**-nek megfelelő.

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metódus

Kikeresi azokat a fájlokat, amelyek megfelelnek a megadott keresési feltételeknek, akár az aktuális objektum által képviselt könyvtárban, akár az abban a könyvtárban gyökerező teljes könyvtárfában.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresett fájlok néveménye |
| searchOption | [SearchOption](../../searchoption/) | Meghatározza, hogy a keresés csak az aktuális objektum által képviselt könyvtárban vagy a teljes, abban a könyvtárban gyökerező könyvtárfában történjen-e |

### Visszatérési érték

Az enumerálható gyűjtemény, amely [FileInfo](../../fileinfo/) objektumokra mutató megosztott pointereket tartalmaz, a megtalált fájlokat reprezentálja, melyek neve **searchPattern**-nek megfelelő.

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)