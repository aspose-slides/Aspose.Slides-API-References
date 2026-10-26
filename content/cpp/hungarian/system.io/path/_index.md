---
title: Path
second_title: Aspose.Slides C++ API-referencia
description: Módszereket biztosít az elérési utak kezeléséhez. Ez egy statikus típus, amelynek nincsenek példányszolgáltatásai. Soha nem szabad példányokat létrehozni belőle semmilyen módon.
type: docs
weight: 339
url: /hu/system.io/path/
---
## Path osztály

Módszereket biztosít az elérési utak kezeléséhez. Ez egy statikus típus, amelynek nincsenek példányszolgáltatásai. Soha nem kell példányokat létrehozni belőle semmilyen módon.

```cpp
class Path
```

## Metódusok

| Méthód | Leírás |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Megváltoztatja a megadott fájlelérési út kiterjesztését. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Megállapítja, hogy a megadott útvonal érvényes-e, azáltal, hogy ellenőrzi, tartalmaz-e érvénytelen karaktereket. Kivétel dobódik, ha az útvonal érvénytelen karaktereket tartalmaz. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Összevonja a megadott útvonal-szegmenseket egyetlen úttá, szükség esetén könyvtár elválasztó karaktereket illeszt be a szegmensek közé. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Összevonja a két megadott útvonal-szegmenst egyetlen úttá, szükség esetén könyvtár elválasztó karaktert illeszt be a szegmensek közé. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Összevonja a három megadott útvonal-szegmenst egyetlen úttá, szükség esetén könyvtár elválasztó karaktereket illeszt be a szegmensek közé. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Összevonja a négy megadott útvonal-szegmenst egyetlen úttá, szükség esetén könyvtár elválasztó karaktereket illeszt be a szegmensek közé. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal által hivatkozott könyvtár nevét. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal által hivatkozott fájl kiterjesztését. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal által hivatkozott fájl nevét. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal által hivatkozott fájl kiterjesztés nélküli nevét. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Átalakítja a megadott útvonalat abszolút útvonallá. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Visszaad egy tömböt, amely olyan karaktereket tartalmaz, amelyek nem engedélyezettek a fájlnevekben. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Visszaad egy tömböt, amely olyan karaktereket tartalmaz, amelyek nem engedélyezettek az útvonalnevekben. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Visszaadja a megadott útvonal gyökérkönyvtárát. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Visszaad egy véletlenszerűen generált fájlnevet. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Létrehoz egy új fájlt egy egyedi névvel, és visszaad a teljes útvonalat hozzá. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Létrehoz egy új fájlt egy egyedi névvel, és visszaad a teljes útvonalat hozzá. A [GetTempFileName_()](./gettempfilename_/) metódus szinonimája. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Visszaadja a jelenlegi felhasználó ideiglenes könyvtárának útvonalát. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Megállapítja, hogy a megadott útvonal olyan fájlra hivatkozik-e, amelynek van kiterjesztése. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Megállapítja, hogy a megadott útvonal tartalmaz-e gyökeret. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalizálja a megadott útvonalat. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Visszaad egy boost::filesystem::path osztály példányt, amely a megadott útvonalat reprezentálja. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Visszaad egy karakterlánc ábrázolást a megadott Boost útvonal objektumról. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Egy alternatív karakter, amely az útvonal könyvtárszintjeinek elválasztására szolgál. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Egy karakter, amely az útvonal könyvtárszintjeinek elválasztására szolgál. |
| static [PathSeparator](./pathseparator/) | Egy elválasztó karakter, amely a környezeti változókban az útvonal karakterláncokat választja el. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Egy kötet elválasztó karakter. |

## Megjegyzések

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Véletlenszerű fájlnevet generál.
  auto filename = Path::GetRandomFileName();

  // Kiírja a fájlnév információit.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
Fájlnév: qhuzkyqv.y6p
Fájlnév kiterjesztés nélkül: qhuzkyqv
Kiterjesztés: .y6p
*/
```

## Lásd még

* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)