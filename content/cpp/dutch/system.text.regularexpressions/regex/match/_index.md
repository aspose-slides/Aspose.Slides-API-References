---
title: Match()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt regex in een string.
type: docs
weight: 66
url: /nl/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Zoekt regex in een string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Doelstring. |

### Retourwaarde

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, int, int) method


Zoekt regex in een string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Doelstring. |
| startat | int | Beginnende index. |
| length | int | Aantal tekens om te doorzoeken (0 om de hele string te doorzoeken). |

### Retourwaarde

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Zoekt naar overeenkomst tussen string en patroon.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| options | [RegexOptions](../../regexoptions/) | Zoekopties. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Time-out. |
| startat | int | [Match](../../match/) beginnende positie. |
| length | int | Aantal tekens om te doorzoeken (0 schakelt limiet uit). |

### Retourwaarde

Eerste overeenkomst gevonden.

## Zie ook

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)