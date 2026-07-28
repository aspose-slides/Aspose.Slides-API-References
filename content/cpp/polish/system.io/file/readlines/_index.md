---
title: ReadLines()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu przy użyciu podanego kodowania znaków i zwraca kolekcję enumerowalną ciągów znaków, z których każdy reprezentuje pojedynczy wiersz zawartości pliku.
type: docs
weight: 326
url: /pl/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metoda


Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu przy użyciu podanego kodowania znaków i zwraca kolekcję enumerowalną ciągów znaków, z których każdy reprezentuje pojedynczy wiersz zawartości pliku.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka pliku do odczytu |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie znaków do użycia |

### Wartość zwracana

Kolekcja enumerowalna ciągów znaków reprezentująca zawartość określonego pliku

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)