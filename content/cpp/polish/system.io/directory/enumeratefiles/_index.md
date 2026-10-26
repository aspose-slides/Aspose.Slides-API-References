---
title: EnumerateFiles()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od tego katalogu.
type: docs
weight: 40
url: /pl/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od tego katalogu.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym ma być przeprowadzone wyszukiwanie |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików, które mają być wyszukane |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma zostać przeprowadzone tylko w podanym katalogu, czy w całym drzewie katalogów rozpoczynającym się od tego katalogu |

### Wartość zwracana

Kolekcja wyliczalna pełnych ścieżek do znalezionych plików, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)