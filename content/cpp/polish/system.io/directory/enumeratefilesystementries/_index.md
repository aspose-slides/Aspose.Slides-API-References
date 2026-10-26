---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się w tym katalogu.
type: docs
weight: 53
url: /pl/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) metoda


Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się w tym katalogu.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym ma być przeprowadzone wyszukiwanie |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów, których należy szukać |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w określonym katalogu, czy w całym drzewie katalogów rozpoczynającym się w określonym katalogu |

### Wartość zwracana

Kolekcja wyliczalna pełnych ścieżek znalezionych plików i katalogów, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klasa [String](../../../system/string/)
* Klasa [Directory](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)