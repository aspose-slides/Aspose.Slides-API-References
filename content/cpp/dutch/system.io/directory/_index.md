---
title: Directory
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden voor het manipuleren van mappen. Dit is een statisch type zonder instantie-services. Je mag onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 235
url: /nl/system.io/directory/
---
## Directory klasse


Bevat methoden voor het manipuleren van mappen. Dit is een statisch type zonder instantie-services. Je mag onder geen enkele omstandigheid instanties ervan maken.

```cpp
class Directory
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Maakt alle mappen in het opgegeven pad aan als deze niet bestaan. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Verwijdert het opgegeven bestand of de opgegeven map. Werpt geen uitzondering. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Bepaalt of het opgegeven pad naar een bestaande map verwijst. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Geeft de aanmaaktijd van de opgegeven entiteit terug als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Geeft de aanmaaktijd van de opgegeven entiteit terug als UTC-tijd. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Geeft de volledige naam (inclusief pad) van de huidige map terug. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Geeft de hoofdmap (root) van het opgegeven pad terug. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die in de opgegeven map is geworteld. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Geeft de laatste toegangstijd van de opgegeven entiteit terug als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Geeft de laatste toegangstijd van de opgegeven entiteit terug als UTC-tijd. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Geeft de laatste schrijftijd van de opgegeven entiteit terug als lokale tijd. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Geeft de laatste schrijftijd van de opgegeven entiteit terug als UTC-tijd. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NIET GEÏMPLENTEERD. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Geeft een shared pointer naar een [DirectoryInfo](../directoryinfo/)-object terug dat de bovenliggende map van de opgegeven entiteit vertegenwoordigt. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verplaatst de opgegeven entiteit naar de nieuwe locatie. Als de te verplaatsen entiteit een map is, wordt deze met al haar inhoud verplaatst. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de aanmaaktijd van de opgegeven entiteit in als lokale tijd. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de aanmaaktijd van de opgegeven entiteit in als UTC-tijd. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Stelt de huidige map in. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de opgegeven entiteit in als lokale tijd. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de opgegeven entiteit in als UTC-tijd. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de opgegeven entiteit in als lokale tijd. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de opgegeven entiteit in als UTC-tijd. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Een alias voor een shared pointer naar een IEnumerable-object dat over een verzameling [String](../../system/string/)-objecten enumerateert. |

## Opmerkingen



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
  // Maak strings die paden naar mappen bevatten.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Controleer of mappen bestaan.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Print de tijdelijk mapinformatie.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## Zie ook

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)