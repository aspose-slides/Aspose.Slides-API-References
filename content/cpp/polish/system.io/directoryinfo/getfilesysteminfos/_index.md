---
title: GetFileSystemInfos()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tablicę zawierającą wskaźniki współdzielone do obiektów FileSystemInfo reprezentujących wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 170
url: /pl/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metoda

Zwraca tablicę zawierającą wskaźniki współdzielone do obiektów [FileSystemInfo](../../filesysteminfo/) reprezentujących wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metoda

Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów, które mają być wyszukane |

### Wartość zwracana

Tablica wskaźników współdzielonych do obiektów [FileSystemInfo](../../filesysteminfo/) reprezentujących znalezione pliki i katalogi, których nazwy pasują do **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metoda

Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów zaczynającym się od katalogu reprezentowanego przez bieżący obiekt.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików i katalogów, które mają być wyszukane |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów zaczynającym się od tego katalogu |

### Wartość zwracana

Tablica wskaźników współdzielonych do obiektów [FileSystemInfo](../../filesysteminfo/) reprezentujących znalezione pliki i katalogi, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klasa [DirectoryInfo](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)