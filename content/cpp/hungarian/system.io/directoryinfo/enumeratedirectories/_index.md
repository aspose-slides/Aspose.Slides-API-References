---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy enumerálható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes könyvtárat.
type: docs
weight: 105
url: /hu/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metódus


Visszaad egy enumerálható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes könyvtárat.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metódus


Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő könyvtárak névmintája |

### Visszatérési érték

Az enumerálható gyűjtemény a megtalált könyvtárakat reprezentáló [DirectoryInfo](../) objektumokra mutató megosztott pointerekkel, amelyek neve egyezik a **searchPattern**-mel

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metódus


Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtárfa struktúrájában.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő könyvtárak névmintája |
| searchOption | [SearchOption](../../searchoption/) | Megadja, hogy a keresést kizárólag az aktuális objektum által képviselt könyvtárban vagy a azt gyökérnek tekintő teljes könyvtárfa struktúrájában kell-e végrehajtani |

### Visszatérési érték

Az enumerálható gyűjtemény a megtalált könyvtárakat reprezentáló [DirectoryInfo](../) objektumokra mutató megosztott pointerekkel, amelyek neve egyezik a **searchPattern**-mel

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)