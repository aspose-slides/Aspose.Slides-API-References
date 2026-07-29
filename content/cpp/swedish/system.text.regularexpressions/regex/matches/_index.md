---
title: Matches()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar alla träffar av regex i angiven sträng genom att matcha upprepade gånger.
type: docs
weight: 79
url: /sv/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Hämtar alla träffar av regex i den givna strängen genom att matcha upprepade gånger.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| startat | int | [Index](../../../system/index/) för att starta matchning vid. |

### Returvärde

Samling av alla funna träffar.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Hämtar alla träffar mellan sträng och mönster.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regexp-mönster. |
| options | [RegexOptions](../../regexoptions/) | Matchningsalternativ. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) startposition. |
| length | int | Antal tecken att söka igenom (0 inaktiverar gräns). |

### Returvärde

Alla träffar funna genom upprepad matchning.

## Se även

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Klass [String](../../../system/string/)
* Klass [Regex](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Text::RegularExpressions](../../)
* Bibliotek [Aspose.Slides](../../../)