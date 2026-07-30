---
title: Path
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Poskytuje metody pro manipulaci s cestami. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.
type: docs
weight: 339
url: /cs/system.io/path/
---
## Třída Path

Poskytuje metody pro manipulaci s cestami. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.

```cpp
class Path
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Změní příponu ve zadané cestě k souboru. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Určuje, zda je zadaná cesta platná kontrolou, zda neobsahuje neplatné znaky. Pokud cesta obsahuje neplatné znaky, je vyvolána výjimka. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Spojí zadané části cesty do jedné cesty a v případě potřeby vloží mezi části znaky oddělovače adresářů. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Spojí dvě zadané části cesty do jedné cesty a v případě potřeby vloží mezi části znak oddělovače adresářů. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Spojí tři zadané části cesty do jedné cesty a v případě potřeby vloží mezi části znaky oddělovače adresářů. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Spojí čtyři zadané části cesty do jedné cesty a v případě potřeby vloží mezi části znaky oddělovače adresářů. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Vrací název adresáře, na který odkazuje zadaná cesta. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Vrací příponu souboru, na který odkazuje zadaná cesta. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Vrací název souboru, na který odkazuje zadaná cesta. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Vrací název souboru bez přípony, na který odkazuje zadaná cesta. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Převádí zadanou cestu na absolutní cestu. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Vrací pole obsahující znaky, které nejsou povoleny v názvech souborů. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Vrací pole obsahující znaky, které nejsou povoleny v názvech cest. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Vrací kořenový adresář zadané cesty. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Vrací náhodně generovaný název souboru. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Vytvoří nový soubor s unikátním názvem a vrátí k němu úplnou cestu. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Vytvoří nový soubor s unikátním názvem a vrátí k němu úplnou cestu. Je synonymem metody [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Vrací cestu do dočasného adresáře aktuálního uživatele. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Určuje, zda zadaná cesta odkazuje na soubor s příponou. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Určuje, zda zadaná cesta obsahuje kořen. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalizuje zadanou cestu. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Vrací instanci třídy boost::filesystem::path, která představuje zadanou cestu. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Vrací řetězcovou reprezentaci zadaného objektu cesty knihovny Boost. |

## Pole

| Pole | Popis |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Alternativní znak používaný k oddělení úrovní adresářů v cestě. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Znak používaný k oddělení úrovní adresářů v cestě. |
| static [PathSeparator](./pathseparator/) | Oddělovač používaný k oddělení řetězců cest v proměnných prostředí. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Znak oddělovače svazku. |

## Poznámky

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Vygeneruje náhodný název souboru.
  auto filename = Path::GetRandomFileName();

  // Vytiskne informace o názvu souboru.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
Název souboru: qhuzkyqv.y6p
Název souboru bez přípony: qhuzkyqv
Přípona: .y6p
*/
```

## Viz také

* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)