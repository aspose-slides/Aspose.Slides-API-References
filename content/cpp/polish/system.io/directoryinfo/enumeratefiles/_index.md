---
title: EnumerateFiles()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca kolekcję wyliczalną zawierającą wszystkie pliki znajdujące się w katalogu reprezentowanym przez bieżący obiekt.
type: docs
weight: 118
url: /pl/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metoda

Zwraca kolekcję wyliczalną zawierającą wszystkie pliki znajdujące się w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```
## DirectoryInfo::EnumerateFiles(const String\&) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazw plików do wyszukania |

### Wartość zwracana

Kolekcja wyliczalna współdzielonych wskaźników do obiektów [FileInfo](../../fileinfo/) reprezentujących znalezione pliki, których nazwy pasują do **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metoda

Wyszukuje pliki spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów rozpoczynającym się od katalogu reprezentowanego przez bieżący obiekt.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Wzorzec nazw plików do wyszukania |
| searchOption | [SearchOption](../../searchoption/) | Określa, czy wyszukiwanie ma być wykonane tylko w katalogu reprezentowanym przez bieżący obiekt, czy w całym drzewie katalogów rozpoczynającym się od katalogu reprezentowanego przez bieżący obiekt |

### Wartość zwracana

Kolekcja wyliczalna współdzielonych wskaźników do obiektów [FileInfo](../../fileinfo/) reprezentujących znalezione pliki, których nazwy pasują do **searchPattern**

## Zobacz także

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)