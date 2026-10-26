---
title: WriteAllText()
second_title: Aspose.Slides for C++ - Referencja API
description: Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje do niego zawartość określonego ciągu znaków przy użyciu podanego kodowania.
type: docs
weight: 469
url: /pl/system.io/file/writealltext/
---
## File::WriteAllText(const String&, const String&, const EncodingPtr&) metoda

Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje do niego zawartość określonego ciągu znaków przy użyciu podanego kodowania.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Plik do utworzenia lub nadpisania |
| contents | const [String](../../../system/string/)& | Tablica ciągów znaków |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | Kodowanie znaków do użycia |

## Zobacz także

* Definicja typu [EncodingPtr](../../../system/encodingptr/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)