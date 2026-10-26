---
title: Match()
second_title: Aspose.Slides för C++ API-referens
description: Matchar regex mot sträng.
type: docs
weight: 66
url: /sv/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) metod

Matchar regex mot sträng.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Målssträng. |

### Returvärde

[Match](../../match/) värde som innehåller matchningsstatus och delmatchningar.

## Regex::Match(const String\&, int, int) metod

Matchar regex mot sträng.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Målssträng. |
| startat | int | Startindex. |
| length | int | Antal tecken att söka igenom (0 för att söka igenom hela strängen). |

### Returvärde

[Match](../../match/) värde som innehåller matchningsstatus och delmatchningar.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metod

Matchar sträng och mönster.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regex-mönster. |
| options | [RegexOptions](../../regexoptions/) | Matchningsalternativ. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tidsgräns. |
| startat | int | [Match](../../match/) börjanposition. |
| length | int | Antal tecken att söka igenom (0 inaktiverar begränsning). |

### Returvärde

Första matchning som hittades.

## Se också

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Klass [String](../../../system/string/)
* Klass [Regex](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Text::RegularExpressions](../../)
* Bibliotek [Aspose.Slides](../../../)