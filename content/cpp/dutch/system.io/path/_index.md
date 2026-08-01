---
title: Path
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt methoden voor het manipuleren van paden. Dit is een statisch type zonder instantiediensten. Je mag onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 339
url: /nl/system.io/path/
---
## Path klasse

Biedt methoden voor het manipuleren van paden. Dit is een statisch type zonder instantie-diensten. Je mag nooit exemplaren ervan maken op welke manier dan ook.

```cpp
class Path
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Wijzigt de extensie in het opgegeven bestandspad. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Bepaalt of het opgegeven pad geldig is door te controleren of het ongeldige tekens bevat. Een uitzondering wordt gegooid als het pad ongeldige tekens bevat. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combineert de opgegeven padsegmenten tot één pad, waarbij indien nodig scheidingstekens tussen de segmenten worden ingevoegd. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combineert twee opgegeven padsegmenten tot één pad, waarbij indien nodig een scheidingsteken tussen de segmenten wordt ingevoegd. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combineert drie opgegeven padsegmenten tot één pad, waarbij indien nodig scheidingstekens tussen de segmenten worden ingevoegd. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combineert vier opgegeven padsegmenten tot één pad, waarbij indien nodig scheidingstekens tussen de segmenten worden ingevoegd. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Retourneert de naam van de directory waarnaar verwezen wordt door het opgegeven pad. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Retourneert de extensie van het bestand waarnaar verwezen wordt door het opgegeven pad. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Retourneert de naam van het bestand waarnaar verwezen wordt door het opgegeven pad. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Retourneert de naam zonder extensie van het bestand waarnaar verwezen wordt door het opgegeven pad. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Converteert het opgegeven pad naar een absoluut pad. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Retourneert een array met tekens die niet zijn toegestaan in bestandsnamen. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Retourneert een array met tekens die niet zijn toegestaan in padnamen. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Retourneert de rootdirectory van het opgegeven pad. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Retourneert een willekeurig gegenereerde bestandsnaam. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Maakt een nieuw bestand met een unieke naam aan en retourneert een volledig pad ernaartoe. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Maakt een nieuw bestand met een unieke naam aan en retourneert een volledig pad ernaartoe. Is een synoniem van [GetTempFileName_()](./gettempfilename_/) methode. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Retourneert het pad van de tijdelijke map van de huidige gebruiker. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Bepaalt of het opgegeven pad verwijst naar een bestand met extensie. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Bepaalt of het opgegeven pad een root bevat. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normaliseert het opgegeven pad. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Retourneert een instantie van de boost::filesystem::path klasse die het opgegeven pad vertegenwoordigt. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Retourneert een tekenreeksrepresentatie van het opgegeven Boost padobject. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Een alternatief teken dat wordt gebruikt om directory-niveaus in een pad te scheiden. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Een teken dat wordt gebruikt om directory-niveaus in een pad te scheiden. |
| static [PathSeparator](./pathseparator/) | Een scheidingsteken dat wordt gebruikt om pad-strings in omgevingsvariabelen te scheiden. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Een volumeschijdings-teken. |

## Opmerkingen

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Genereer een willekeurige bestandsnaam.
  auto filename = Path::GetRandomFileName();

  // Print informatie over de bestandsnaam.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Deze codevoorbeeld produceert de volgende output:
Bestandsnaam: qhuzkyqv.y6p
Bestandsnaam zonder extensie: qhuzkyqv
Extensie: .y6p
*/
```

## Zie ook

* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)