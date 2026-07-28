---
title: GetFileSystemEntries()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu.
type: docs
weight: 92
url: /pl/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) metoda


Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania, zarówno w podanym katalogu, jak i w całym drzewie katalogów rozpoczynającym się od podanego katalogu.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Pełna lub względna ścieżka do katalogu, w którym ma być prowadzone wyszukiwanie |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów, które mają zostać wyszukane |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w podanym katalogu, czy w całym drzewie katalogów rozpoczynającym się od podanego katalogu |

### Wartość zwracana

Tablica pełnych ścieżek znalezionych plików i katalogów, których nazwy pasują do **searchPattern**

## Zobacz także

* Wyliczenie [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [Directory](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)