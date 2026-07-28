---
title: EnumerateDirectories()
second_title: Aspose.Slides dla C++ Odwołanie do API
description: Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w określonym katalogu, jak i w całym drzewie katalogów z korzeniem w określonym katalogu.
type: docs
weight: 27
url: /pl/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) metoda


Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w określonym katalogu, jak i w całym drzewie katalogów z korzeniem w określonym katalogu.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym należy wyszukiwać |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów, które mają być wyszukane |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w określonym katalogu, czy w całym drzewie katalogów z korzeniem w określonym katalogu |

### Wartość zwracana

Zbiór wyliczalny pełnych ścieżek do znalezionych katalogów, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klasa [String](../../../system/string/)
* Klasa [Directory](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)