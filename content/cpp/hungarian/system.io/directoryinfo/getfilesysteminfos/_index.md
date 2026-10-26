---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a FileSystemInfo objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes fájlt és könyvtárat képviselik.
type: docs
weight: 170
url: /hu/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metódus

Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a [FileSystemInfo](../../filesysteminfo/) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes fájlt és könyvtárat képviselik.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metódus

Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok és könyvtárak név mintája |

### Visszatérési érték

Egy tömb megosztott mutatókat tartalmaz a [FileSystemInfo](../../filesysteminfo/) objektumokra, amelyek a megtalált fájlok és könyvtárak, és neveik megegyeznek a **searchPattern** mintával.

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metódus

Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek, akár az aktuális objektum által képviselt könyvtárban, akár az azt gyökérnek tekintő teljes könyvtárfában.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő fájlok és könyvtárak név mintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést csak az aktuális objektum által képviselt könyvtárban kell-e végrehajtani, vagy az azt gyökérnek tekintő teljes könyvtárfában. |

### Visszatérési érték

Egy tömb megosztott mutatókat tartalmaz a [FileSystemInfo](../../filesysteminfo/) objektumokra, amelyek a megtalált fájlok és könyvtárak, és neveik megegyeznek a **searchPattern** mintával.

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Osztály [DirectoryInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)