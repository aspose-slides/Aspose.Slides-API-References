---
title: AppendAllLines()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dodaje ciągi znaków z określonej kolekcji ciągów znaków do wskazanego pliku przy użyciu określonego kodowania, zapisując każdy ciąg w nowej linii. Jeśli określony plik nie istnieje, zostaje utworzony. Plik jest zamykany po zapisaniu wszystkich ciągów.
type: docs
weight: 1
url: /pl/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metoda

Dodaje ciągi znaków z określonej kolekcji ciągów znaków do określonego pliku przy użyciu określonego kodowania, zapisując każdy ciąg w nowej linii. Jeśli określony plik nie istnieje, zostaje utworzony. Plik jest zamykany po zapisaniu wszystkich ciągów.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka pliku, do którego mają zostać dodane ciągi znaków |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Ciągi znaków do zapisania w pliku |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie znaków do użycia |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasa [String](../../../system/string/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)