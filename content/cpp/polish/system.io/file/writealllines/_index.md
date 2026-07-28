---
title: WriteAllLines()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje wszystkie łańcuchy znaków z określonej kolekcji enumerable do niego, każdy łańcuch w nowej linii, używając podanego kodowania.
type: docs
weight: 456
url: /pl/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje wszystkie łańcuchy znaków z określonej kolekcji enumerable do niego, każdy łańcuch w nowej linii, używając podanego kodowania.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Plik do utworzenia lub nadpisania |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Kolekcja enumerable łańcuchów znaków |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Używane kodowanie znaków |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method

Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje wszystkie łańcuchy znaków z określonej tablicy łańcuchów do niego, każdy łańcuch w nowej linii, używając podanego kodowania.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Plik do utworzenia lub nadpisania |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Tablica łańcuchów znaków |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Używane kodowanie znaków |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)