---
title: Matches()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wszystkie dopasowania wyrażenia regularnego w podanym ciągu, dopasowując wielokrotnie.
type: docs
weight: 79
url: /pl/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) metoda


Gets all matches of regex in given string by matching repeatedly.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg wejściowy. |
| startat | int | [Index](../../../system/index/) aby rozpocząć dopasowywanie od. |

### Wartość zwracana

Kolekcja wszystkich znalezionych dopasowań.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metoda


Gets all matches between string and pattern.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| options | [RegexOptions](../../regexoptions/) | Opcje dopasowywania. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Limit czasu. |
| startat | int | [Match](../../match/) pozycja początkowa. |
| length | int | Liczba znaków do przeszukania (0 wyłącza limit). |

### Wartość zwracana

Wszystkie dopasowania znalezione poprzez wielokrotne dopasowywanie.

## Zobacz także

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)