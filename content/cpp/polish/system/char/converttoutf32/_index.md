---
title: ConvertToUtf32()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje określoną parę surogatów UTF-16 na jednostkę kodu UTF-32.
type: docs
weight: 287
url: /pl/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metoda


Konwertuje określoną parę surogatów UTF-16 na jednostkę kodu UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| highSurrogate | char_t | Wysoki surogat pary surogatów UTF-16 do konwersji |
| lowSurrogate | char_t | Niski surogat pary surogatów UTF-16 do konwersji |

### Wartość zwracana

Jednostka kodu UTF-32 uzyskana w wyniku konwersji

## Char::ConvertToUtf32(const String\&, int) metoda


Konwertuje wartość znaku zakodowanego w UTF-16 lub pary surogatów znajdującą się w określonej pozycji w łańcuchu znaków na jednostkę kodu UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Łańcuch znaków zawierający znak lub parę surogatów |
| index | int | Pozycja indeksowa znaku lub pary surogatów w podanym łańcuchu znaków |

### Wartość zwracana

Jednostka kodu UTF-32 uzyskana w wyniku konwersji

## Zobacz także

* Klasa [Char](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)