---
title: Directory
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zawiera metody do manipulacji katalogami. Jest to typ statyczny bez usług instancji. Nie powinno się tworzyć jego instancji w żaden sposób.
type: docs
weight: 235
url: /pl/system.io/directory/
---
## Directory klasa

Zawiera metody do manipulacji katalogami. Jest to typ statyczny bez usług instancji. Nie powinno się tworzyć jego instancji w żaden sposób.

```cpp
class Directory
```

## Metody

| Method | Opis |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Tworzy wszystkie katalogi w określonej ścieżce, jeśli nie istnieją. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Usuwa określony plik lub katalog. Nie zgłasza wyjątków. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Określa, czy podana ścieżka odnosi się do istniejącego katalogu. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Zwraca czas utworzenia określonego obiektu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Zwraca czas utworzenia określonego obiektu jako czas UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Zwraca pełną nazwę (włącznie ze ścieżką) bieżącego katalogu. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Zwraca katalog główny określonej ścieżki. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego dostępu do określonego obiektu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego dostępu do określonego obiektu jako czas UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego zapisu określonego obiektu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego zapisu określonego obiektu jako czas UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NIE ZAIMPLEMENTOWANO. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Zwraca wskaźnik współdzielony do obiektu [DirectoryInfo](../directoryinfo/) reprezentującego katalog nadrzędny określonego obiektu. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Przenosi określony obiekt do nowej lokalizacji. Jeśli przenoszony obiekt jest katalogiem, jest przenoszony wraz ze wszystkimi jego zawartościami. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas utworzenia określonego obiektu jako czas lokalny. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas utworzenia określonego obiektu jako czas UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Ustawia bieżący katalog. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu do określonego obiektu jako czas lokalny. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu do określonego obiektu jako czas UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu określonego obiektu jako czas lokalny. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu określonego obiektu jako czas UTC. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Alias dla wskaźnika współdzielonego do obiektu IEnumerable, który wylicza zestaw obiektów [String](../../system/string/). |

## Uwagi



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
  // Utwórz ciągi zawierające ścieżki do katalogów.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Sprawdź, czy katalogi istnieją.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Wypisz informacje o katalogu tymczasowym.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Katalog 'C:\' istnieje.
Katalog 'C:\Some directory' nie istnieje.
Katalog 'C:\Users\lanor\AppData\Local\Temp\' istnieje.
Czas utworzenia: 27.08.2021 14:21:42
Czas ostatniego dostępu: 07.10.2021 12:16:41
Czas ostatniego zapisu: 07.10.2021 12:16:41
*/
```

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)