---
title: OpenText()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Otwiera określony istniejący plik w trybie odczytu tekstu przy użyciu kodowania UTF-8 bez udostępniania.
type: docs
weight: 261
url: /pl/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) metoda


Otwiera istniejący, określony plik w trybie odczytu tekstu przy użyciu kodowania UTF-8 bez udostępniania.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka do pliku, który ma zostać otwarty |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie znaków, które ma być użyte |

### Wartość zwracana

Wskaźnik współdzielony do obiektu [StreamWriter](../../streamwriter/) powiązanego z otwartym plikiem

## Zobacz także

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)