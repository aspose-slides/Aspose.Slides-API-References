---
title: GetDirectories()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a DirectoryInfo objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat reprezentálják.
type: docs
weight: 144
url: /hu/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() módszer


Visszaad egy tömböt, amely megosztott mutatókat tartalmaz a [DirectoryInfo](../) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat reprezentálják.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) módszer


A megadott keresési feltételeknek megfelelő könyvtárakat keresi az aktuális objektum által képviselt könyvtárban.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő könyvtárak nevének mintája |

### Visszatérési érték

Egy tömb, amely megosztott mutatókat tartalmaz a [DirectoryInfo](../) objektumokra, amelyek a megtalált könyvtárakat reprezentálják, és amelyek neve megegyezik a **searchPattern** mintával.

## DirectoryInfo::GetDirectories(const String\&, SearchOption) módszer


A megadott keresési feltételeknek megfelelő könyvtárakat keresi vagy az aktuális objektum által képviselt könyvtárban, vagy az abból kiinduló teljes könyvtárfában.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | A keresendő könyvtárak nevének mintája |
| searchOption | [SearchOption](../../searchoption/) | Meghatározza, hogy a keresés csak az aktuális objektum által képviselt könyvtárban vagy az abból kiinduló teljes könyvtárfában kell-e történjen |

### Visszatérési érték

Egy tömb, amely megosztott mutatókat tartalmaz a [DirectoryInfo](../) objektumokra, amelyek a megtalált könyvtárakat reprezentálják, és amelyek neve megegyezik a **searchPattern** mintával.

## Lásd még

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Osztály [DirectoryInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)