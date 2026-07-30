---
title: Match()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Porovnává regulární výraz s řetězcem.
type: docs
weight: 66
url: /cs/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) metoda

Porovnává regulární výraz s řetězcem.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cílový řetězec. |

### Návratová hodnota

[Match](../../match/) hodnota obsahující stav shody a podshody.

## Regex::Match(const String\&, int, int) metoda

Porovnává regulární výraz s řetězcem.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cílový řetězec. |
| startat | int | Počáteční index. |
| length | int | Počet znaků, které se mají prohledat (0 pro prohledání celého řetězce). |

### Návratová hodnota

[Match](../../match/) hodnota obsahující stav shody a podshody.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metoda

Porovnává řetězec a vzor.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Vzor regulárního výrazu. |
| options | [RegexOptions](../../regexoptions/) | Možnosti porovnání. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Časový limit. |
| startat | int | [Match](../../match/) počáteční pozice. |
| length | int | Počet znaků, které se mají prohledat (0 ruší limit). |

### Návratová hodnota

První nalezená shoda.

## Viz také

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Třída [String](../../../system/string/)
* Třída [Regex](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Text::RegularExpressions](../../)
* Knihovna [Aspose.Slides](../../../)