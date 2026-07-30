---
title: IsMatch()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává regulární výraz s řetězcem.
type: docs
weight: 53
url: /cs/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metoda

Porovná regulární výraz se řetězcem.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cílový řetězec. |
| startat | int | Počáteční index. |

### Návratová hodnota

True pokud řetězec odpovídá regulárnímu výrazu, false jinak.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metoda

Kontroluje, zda řetězec odpovídá vzoru.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Vzor regulárního výrazu. |
| options | [RegexOptions](../../regexoptions/) | Možnosti porovnání. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Časový limit. |
| startat | int | [Match](../../match/) počáteční pozice. |

### Návratová hodnota

True pokud je nalezena shoda, false jinak.

## Viz také

* Enum [RegexOptions](../../regexoptions/)
* Třída [String](../../../system/string/)
* Třída [Regex](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Text::RegularExpressions](../../)
* Knihovna [Aspose.Slides](../../../)