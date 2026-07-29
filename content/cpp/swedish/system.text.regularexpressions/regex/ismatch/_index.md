---
title: IsMatch()
second_title: Aspose.Slides för C++ API-referens
description: Matchar regex mot sträng.
type: docs
weight: 53
url: /sv/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metod

Matchar reguljärt uttryck mot sträng.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Målssträng. |
| startat | int | Startindex. |

### Returvärde

True om strängen matchar reguljärt uttryck, false annars.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metod

Kontrollerar om strängen matchar mönstret.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Reguljärt uttrycksmönster. |
| options | [RegexOptions](../../regexoptions/) | Matchningsalternativ. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tidsgräns. |
| startat | int | [Match](../../match/) börjanposition. |

### Returvärde

True om en matchning hittas, false annars.

## Se även

* Enum [RegexOptions](../../regexoptions/)
* Klass [String](../../../system/string/)
* Klass [Regex](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Text::RegularExpressions](../../)
* Bibliotek [Aspose.Slides](../../../)