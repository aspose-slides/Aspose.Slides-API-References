---
title: Directory
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje metody pro manipulaci s adresáři. Jedná se o statický typ bez instančních služeb. Neměli byste jej nikdy vytvářet jako instanci jakýmkoli způsobem.
type: docs
weight: 235
url: /cs/system.io/directory/
---
## Třída Directory

Obsahuje metody pro manipulaci s adresáři. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem.

```cpp
class Directory
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Vytvoří všechny adresáře ve zadané cestě, pokud neexistují. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Odstraní zadaný soubor nebo adresář. Nevyvolává výjimku. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá adresáře, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá soubory, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá soubory a adresáře, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Určuje, zda zadaná cesta odkazuje na existující adresář. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Vrátí čas vytvoření zadané entity jako místní čas. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Vrátí čas vytvoření zadané entity jako čas UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Vrátí úplný název (včetně cesty) aktuálního adresáře. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá adresáře, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Vrátí kořenový adresář zadané cesty. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá soubory, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledá soubory a adresáře, které splňují zadaná kritéria hledání, buď ve specifikovaném adresáři, nebo v celém stromu adresářů kořeněném ve specifikovaném adresáři. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Vrátí čas posledního přístupu k zadané entitě jako místní čas. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Vrátí čas posledního přístupu k zadané entitě jako čas UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Vrátí čas posledního zápisu zadané entity jako místní čas. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Vrátí čas posledního zápisu zadané entity jako čas UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NEIMPLEMENTOVÁNO. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Vrátí sdílený ukazatel na objekt [DirectoryInfo](../directoryinfo/) představující nadřazený adresář zadané entity. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Přesune zadanou entitu na nové místo. Pokud je přesouvaná entita adresář, je přesunut se všemi svými obsahem. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas vytvoření zadané entity jako místní čas. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas vytvoření zadané entity jako čas UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Nastaví aktuální adresář. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k zadané entitě jako místní čas. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k zadané entitě jako čas UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu zadané entity jako místní čas. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu zadané entity jako čas UTC. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Alias pro sdílený ukazatel na objekt IEnumerable, který enumeruje sadu objektů [String](../../system/string/). |

## Poznámky

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
  // Vytvořte řetězce, které obsahují cesty k adresářům.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Zkontrolujte, zda adresáře existují.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Vytiskněte informace o dočasném adresáři.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Tento příklad kódu vytiskne následující výstup:
Adresář 'C:\' existuje.
Adresář 'C:\Some directory' neexistuje.
Adresář 'C:\Users\lanor\AppData\Local\Temp\' existuje.
Čas vytvoření: 27.08.2021 14:21:42
Čas posledního přístupu: 07.10.2021 12:16:41
Čas posledního zápisu: 07.10.2021 12:16:41
*/
```

## Viz také

* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)