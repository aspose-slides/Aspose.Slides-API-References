---
title: Directory
second_title: Aspose.Slides C++ API Referencia
description: Metódusokat tartalmaz a könyvtárak kezeléséhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Semmilyen módon sem szabad példányokat létrehozni belőle.
type: docs
weight: 235
url: /hu/system.io/directory/
---
## Directory osztály

Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Directory
```

## Methods

| Metódus | Leírás |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Létrehozza az összes könyvtárat a megadott útvonalon, ha azok nem léteznek. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Eltávolítja a megadott fájlt vagy könyvtárat. Nem dob kivételt. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan könyvtárakat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan fájlokat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan fájlokat és könyvtárakat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Megállapítja, hogy a megadott útvonal létező könyvtárra mutat-e. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás létrehozási időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás létrehozási időpontját UTC időként. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Visszaadja az aktuális könyvtár teljes nevét (az útvonallal együtt). |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan könyvtárakat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal gyökérkönyvtárát. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan fájlokat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres olyan fájlokat és könyvtárakat, amelyek megfelelnek a megadott keresési kritériumoknak, akár a megadott könyvtárban, akár a megaddott könyvtárban gyökerező teljes könyvtárfában. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó hozzáférési időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó hozzáférési időpontját UTC időként. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó írási időpontját helyi időként. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Visszaadja a megadott entitás utolsó írási időpontját UTC időként. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NEM IMPLEMENTÁLT. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Visszaad egy megosztott mutatót a [DirectoryInfo](../directoryinfo/) objektumra, amely a megadott entitás szülőkönyvtárát képviseli. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Áthelyezi a megadott entitást az új helyre. Ha a mozgatandó entitás egy könyvtár, akkor annak teljes tartalma is áthelyeződik. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás létrehozási időpontját helyi időként. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás létrehozási időpontját UTC időként. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Beállítja az aktuális könyvtárat. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó hozzáférési időpontját helyi időként. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó hozzáférési időpontját UTC időként. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó írási időpontját helyi időként. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Beállítja a megadott entitás utolsó írási időpontját UTC időként. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Egy alias egy megosztott mutatóhoz az IEnumerable objektumra, amely egy [String](../../system/string/) objektumok halmazát enumerálja. |

## Megjegyzések



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Létrehozza a könyvtárak elérési útvonalait tartalmazó karakterláncokat.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Ellenőrizze, hogy a könyvtárak léteznek-e.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Kiírja az ideiglenes könyvtár információit.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet állítja elő:
A könyvtár 'C:\' létezik.
A könyvtár 'C:\Some directory' nem létezik.
A könyvtár 'C:\Users\lanor\AppData\Local\Temp\' létezik.
Létrehozás időpontja: 27.08.2021 14:21:42
Utolsó hozzáférési idő: 07.10.2021 12:16:41
Utolsó írási idő: 07.10.2021 12:16:41
*/
```

## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)