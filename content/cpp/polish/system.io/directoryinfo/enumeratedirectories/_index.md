---
title: EnumerateDirectories()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wyliczalną kolekcję zawierającą wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 105
url: /pl/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metoda


Zwraca kolekcję wyliczalną zawierającą wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metoda


Wyszukuje katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów do wyszukania |

### Wartość zwracana

Kolekcja wyliczalna udostępnionych wskaźników do [DirectoryInfo](../) obiektów reprezentujących znalezione katalogi, których nazwy pasują do **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metoda


Wyszukuje katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt |

### Wartość zwracana

Kolekcja wyliczalna udostępnionych wskaźników do [DirectoryInfo](../) obiektów reprezentujących znalezione katalogi, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [DirectoryInfo](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)