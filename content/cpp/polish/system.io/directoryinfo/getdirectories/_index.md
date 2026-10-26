---
title: GetDirectories()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów DirectoryInfo reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 144
url: /pl/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() metoda

Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów [DirectoryInfo](../) reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) metoda

Wyszukuje katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów do wyszukania |

### Wartość zwracana

Tablica współdzielonych wskaźników do obiektów [DirectoryInfo](../) reprezentujących znalezione katalogi, których nazwy pasują do **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) metoda

Wyszukuje katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeń stanowi katalog reprezentowany przez bieżący obiekt.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy katalogów do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonywane tylko w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów, którego korzeń stanowi katalog reprezentowany przez bieżący obiekt |

### Wartość zwracana

Tablica współdzielonych wskaźników do obiektów [DirectoryInfo](../) reprezentujących znalezione katalogi, których nazwy pasują do **searchPattern**

## Zobacz także

* Wyliczenie [SearchOption](../../searchoption/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klasa [DirectoryInfo](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)