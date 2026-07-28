---
title: GetDirectories()
second_title: Aspose.Slides dla C++ - referencja API
description: Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w określonym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od tego katalogu.
type: docs
weight: 66
url: /pl/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) method


Wyszukuje katalogi spełniające określone kryteria wyszukiwania, zarówno w określonym katalogu, jak i w całym drzewie katalogów zaczynającym się od tego katalogu.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym należy wyszukiwać |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów, które mają być wyszukane |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być przeprowadzone tylko w określonym katalogu, czy w całym drzewie katalogów zaczynającym się od określonego katalogu |

### Wartość zwracana

Tablica pełnych ścieżek znalezionych katalogów, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)