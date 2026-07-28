---
title: Path
second_title: Referencja API Aspose.Slides dla C++
description: Udostępnia metody do manipulowania ścieżkami. Jest to typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 339
url: /pl/system.io/path/
---
## Klasa Path

Udostępnia metody do manipulowania ścieżkami. To jest typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Path
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zmienia rozszerzenie w określonej ścieżce pliku. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Określa, czy podana ścieżka jest prawidłowa, sprawdzając, czy zawiera nieprawidłowe znaki. Zostaje zgłoszony wyjątek, jeśli ścieżka zawiera nieprawidłowe znaki. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Łączy określone segmenty ścieżki w pojedynczą ścieżkę, wstawiając znaki separatora katalogów pomiędzy segmenty, jeśli to konieczne. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Łączy dwa określone segmenty ścieżki w jedną ścieżkę, wstawiając znak separatora katalogów pomiędzy segmenty, jeśli to konieczne. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Łączy trzy określone segmenty ścieżki w jedną ścieżkę, wstawiając znaki separatora katalogów pomiędzy segmenty, jeśli to konieczne. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Łączy cztery określone segmenty ścieżki w jedną ścieżkę, wstawiając znaki separatora katalogów pomiędzy segmenty, jeśli to konieczne. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Zwraca nazwę katalogu wskazanego przez podaną ścieżkę. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Zwraca rozszerzenie pliku wskazanego przez podaną ścieżkę. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Zwraca nazwę pliku wskazanego przez podaną ścieżkę. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Zwraca nazwę pliku bez rozszerzenia wskazanego przez podaną ścieżkę. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Konwertuje podaną ścieżkę na ścieżkę bezwzględną. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Zwraca tablicę zawierającą znaki niedozwolone w nazwach plików. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Zwraca tablicę zawierającą znaki niedozwolone w nazwach ścieżek. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Zwraca katalog główny podanej ścieżki. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Zwraca losowo wygenerowaną nazwę pliku. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Tworzy nowy plik o unikalnej nazwie i zwraca pełną ścieżkę do niego. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Tworzy nowy plik o unikalnej nazwie i zwraca pełną ścieżkę do niego. Jest synonimem metody [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Zwraca ścieżkę do tymczasowego katalogu bieżącego użytkownika. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Określa, czy podana ścieżka odwołuje się do pliku z rozszerzeniem. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Określa, czy podana ścieżka zawiera korzeń. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalizuje podaną ścieżkę. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Zwraca instancję klasy boost::filesystem::path, która reprezentuje podaną ścieżkę. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Zwraca ciąg znaków reprezentujący podany obiekt ścieżki Boost. |

## Pola

| Pole | Opis |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Alternatywny znak używany do rozdzielania poziomów katalogów w ścieżce. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Znak używany do rozdzielania poziomów katalogów w ścieżce. |
| static [PathSeparator](./pathseparator/) | Znak separatora używany do oddzielania ciągów ścieżek w zmiennych środowiskowych. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Znak separatora wolumenu. |

## Uwagi

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Wygeneruj losową nazwę pliku.
  auto filename = Path::GetRandomFileName();

  // Wypisz informacje o nazwie pliku.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Zobacz też

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)