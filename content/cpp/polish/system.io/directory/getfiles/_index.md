---
title: GetFiles()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od tego katalogu.
type: docs
weight: 79
url: /pl/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od tego katalogu.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym ma być wyszukiwanie |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w podanym katalogu, czy w całym drzewie katalogów rozpoczynającym się od tego katalogu |

### Wartość zwracana

Tablica pełnych ścieżek znalezionych plików, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [Directory](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)