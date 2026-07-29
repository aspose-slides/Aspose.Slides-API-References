---
title: Directory
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 235
url: /sv/system.io/directory/
---
## Directory klass

Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Directory
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Skapar alla kataloger i den angivna sökvägen om de inte finns. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Tar bort den angivna filen eller katalogen. Kastar inte ett undantag. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Bestämmer om den angivna sökvägen refererar till en befintlig katalog. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Returnerar skapandetiden för den angivna enheten som lokal tid. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Returnerar skapandetiden för den angivna enheten som UTC-tid. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Returnerar det fullständiga namnet (inklusive sökväg) för den aktuella katalogen. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Returnerar rotkatalogen för den angivna sökvägen. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Returnerar sista åtkomsttiden för den angivna enheten som lokal tid. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Returnerar sista åtkomsttiden för den angivna enheten som UTC-tid. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Returnerar sista skrivtiden för den angivna enheten som lokal tid. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Returnerar sista skrivtiden för den angivna enheten som UTC-tid. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | INTE IMPLEMENTERAD. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Returnerar en delad pekare till [DirectoryInfo](../directoryinfo/)-objekt som representerar föräldrakatalogen för den angivna enheten. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Flyttar den angivna enheten till den nya platsen. Om enheten som ska flyttas är en katalog flyttas den med allt dess innehåll. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter skapandetiden för den angivna enheten som lokal tid. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter skapandetiden för den angivna enheten som UTC-tid. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Sätter den aktuella katalogen. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter sista åtkomsttiden för den angivna enheten som lokal tid. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter sista åtkomsttiden för den angivna enheten som UTC-tid. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter sista skrivtiden för den angivna enheten som lokal tid. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sätter sista skrivtiden för den angivna enheten som UTC-tid. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Ett alias för en delad pekare till IEnumerable-objekt som enumererar över en uppsättning [String](../../system/string/)-objekt. |

## Anmärkningar



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
  // Skapa strängar som innehåller sökvägar till kataloger.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Kontrollera om kataloger finns.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Skriv ut information om temporärkatalogen.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Detta kodexempel producerar följande utskrift:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)