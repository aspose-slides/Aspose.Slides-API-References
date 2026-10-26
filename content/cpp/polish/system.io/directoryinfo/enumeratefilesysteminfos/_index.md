---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wyliczalną kolekcję zawierającą wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 131
url: /pl/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metoda

Zwraca kolekcję wyliczalną zawierającą wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metoda

Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów do wyszukania |

### Wartość zwracana

Kolekcja wyliczalna wskaźników współdzielonych do obiektów [FileSystemInfo](../../filesysteminfo/) reprezentujących znalezione pliki i katalogi, których nazwy pasują do **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metoda

Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów rozpoczynającym się od katalogu reprezentowanego przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma zostać przeprowadzone wyłącznie w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów rozpoczynającym się od katalogu reprezentowanego przez bieżący obiekt |

### Wartość zwracana

Kolekcja wyliczalna wskaźników współdzielonych do obiektów [FileSystemInfo](../../filesysteminfo/) reprezentujących znalezione pliki i katalogi, których nazwy pasują do **searchPattern**

## Zobacz także

* Wyliczenie [SearchOption](../../searchoption/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [DirectoryInfo](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)