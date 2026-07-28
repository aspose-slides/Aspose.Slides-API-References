---
title: Match()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dopasowuje wyrażenie regularne do ciągu znaków.
type: docs
weight: 66
url: /pl/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) metoda


Dopasowuje wyrażenie regularne do ciągu znaków.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg docelowy. |

### Wartość zwracana

[Match](../../match/) wartość zawierająca status dopasowania i poddopasowania.

## Regex::Match(const String\&, int, int) metoda


Dopasowuje wyrażenie regularne do ciągu znaków.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg docelowy. |
| startat | int | Indeks początkowy. |
| length | int | Liczba znaków do przeszukania (0 aby przeszukać cały ciąg). |

### Wartość zwracana

[Match](../../match/) wartość zawierająca status dopasowania i poddopasowania.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metoda


Dopasowuje ciąg i wzorzec.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| options | [RegexOptions](../../regexoptions/) | Opcje dopasowania. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Limit czasu. |
| startat | int | [Match](../../match/) początkowa pozycja. |
| length | int | Liczba znaków do przeszukania (0 wyłącza limit). |

### Wartość zwracana

Pierwsze znalezione dopasowanie.

## Zobacz także

* Wyliczenie [RegexOptions](../../regexoptions/)
* Definicja typu [MatchPtr](../../matchptr/)
* Klasa [String](../../../system/string/)
* Klasa [Regex](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Text::RegularExpressions](../../)
* Biblioteka [Aspose.Slides](../../../)