---
title: Matches()
second_title: Aspose.Slides pro C++ API Reference
description: Získá všechny shody regulárního výrazu v zadaném řetězci opakovaným vyhledáváním.
type: docs
weight: 79
url: /cs/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) metoda


Získá všechny shody regexu v zadaném řetězci opakovaným vyhledáváním.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| startat | int | [Index](../../../system/index/) k zahájení porovnávání. |

### Návratová hodnota

Sbírka všech nalezených shod.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metoda


Získá všechny shody mezi řetězcem a vzorem.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Vzor regulárního výrazu. |
| options | [RegexOptions](../../regexoptions/) | Možnosti porovnávání. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Časový limit. |
| startat | int | [Match](../../match/) počáteční pozice. |
| length | int | Počet znaků k prohledání (0 deaktivuje omezení). |

### Návratová hodnota

Všechny shody nalezené opakovaným vyhledáváním.

## Viz také

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Třída [String](../../../system/string/)
* Třída [Regex](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)