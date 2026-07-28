---
title: GetFiles()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów FileInfo reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 157
url: /pl/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metoda

Zwraca tablicę zawierającą współdzielone wskaźniki do [FileInfo](../../fileinfo/) obiektów reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików do wyszukania |

### Wartość zwracana

Tablica współdzielonych wskaźników do [FileInfo](../../fileinfo/) obiektów reprezentujących znalezione pliki, których nazwy pasują do **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów mającym swój korzeń w katalogu reprezentowanym przez bieżący obiekt.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazwy plików do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane wyłącznie w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów mającym swój korzeń w katalogu reprezentowanym przez bieżący obiekt |

### Wartość zwracana

Tablica współdzielonych wskaźników do [FileInfo](../../fileinfo/) obiektów reprezentujących znalezione pliki, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)