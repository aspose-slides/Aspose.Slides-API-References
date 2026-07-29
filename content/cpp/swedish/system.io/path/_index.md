---
title: Path
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 339
url: /sv/system.io/path/
---
## Path klass


Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Path
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ändrar filändelsen i den angivna filsökvägen. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Bestämmer om den angivna sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Kombinerar de angivna sökvägssegmenten till en enda sökväg och sätter in katalogseparatorer mellan segmenten om nödvändigt. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombinerar de angivna sökvägssegmenten till en enda sökväg och sätter in katalogseparatorer mellan segmenten om nödvändigt. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombinerar de angivna sökvägssegmenten till en enda sökväg och sätter in katalogseparatorer mellan segmenten om nödvändigt. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kombinerar de angivna sökvägssegmenten till en enda sökväg och sätter in katalogseparatorer mellan segmenten om nödvändigt. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Returnerar namnet på den katalog som refereras av den angivna sökvägen. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Returnerar filens ändelse för den fil som refereras av den angivna sökvägen. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Returnerar namnet på filen som refereras av den angivna sökvägen. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Returnerar filens namn utan ändelse för den fil som refereras av den angivna sökvägen. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Konverterar den angivna sökvägen till en absolut sökväg. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Returnerar en array som innehåller tecken som inte är tillåtna i filnamn. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Returnerar en array som innehåller tecken som inte är tillåtna i sökvägsnamn. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Returnerar rotkatalogen för den angivna sökvägen. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Returnerar ett slumpmässigt genererat filnamn. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Skapar en ny fil med ett unikt namn och returnerar en fullständig sökväg till den. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Skapar en ny fil med ett unikt namn och returnerar en fullständig sökväg till den. Är en synonym till [GetTempFileName_()](./gettempfilename_/) metod. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Returnerar sökvägen till den aktuella användarens temporära katalog. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Bestämmer om den angivna sökvägen refererar till en fil med ändelse. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Bestämmer om den angivna sökvägen innehåller en rot. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normaliserar den angivna sökvägen. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Returnerar en instans av boost::filesystem::path-klassen som representerar den angivna sökvägen. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Returnerar en strängrepresentation av den angivna Boost's path-objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Ett alternativt tecken som används för att separera katalognivåer i en sökväg. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Ett tecken som används för att separera katalognivåer i en sökväg. |
| static [PathSeparator](./pathseparator/) | Ett separator-tecken som används för att separera sökvägssträngar i miljövariabler. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Ett volymseparator-tecken. |
## Anmärkningar



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Generera ett slumpmässigt filnamn.
  auto filename = Path::GetRandomFileName();

  // Skriv ut information om filnamnet.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Detta kodexempel producerar följande utdata:
Filnamn: qhuzkyqv.y6p
Filnamn utan ändelse: qhuzkyqv
Ändelse: .y6p
*/
```

## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)