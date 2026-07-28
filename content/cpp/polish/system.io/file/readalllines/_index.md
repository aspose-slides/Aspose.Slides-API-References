---
title: ReadAllLines()
second_title: Odwołanie API Aspose.Slides dla C++
description: Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu do tablicy ciągów znaków, używając podanego kodowania znaków.
type: docs
weight: 300
url: /pl/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metoda

Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu do tablicy ciągów znaków, używając określonego kodowania znaków.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka pliku do odczytania |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie znaków do użycia |

## Wartość zwracana

Tablica ciągów znaków, z których każdy element reprezentuje pojedynczy wiersz z określonego pliku

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [EncodingPtr](../../../system/encodingptr/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)