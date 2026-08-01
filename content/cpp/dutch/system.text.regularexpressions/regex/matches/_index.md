---
title: Matches()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt alle overeenkomsten van regex op in de opgegeven tekenreeks door herhaaldelijk te matchen.
type: docs
weight: 79
url: /nl/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method

Haalt alle overeenkomsten van regex op in de opgegeven tekenreeks door herhaaldelijk te matchen.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| startat | int | [Index](../../../system/index/) om te beginnen met matchen. |

### Retourwaarde

Collectie van alle gevonden overeenkomsten.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method

Haalt alle overeenkomsten tussen tekenreeks en patroon op.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| options | [RegexOptions](../../regexoptions/) | Matchopties. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) beginpositie. |
| length | int | Aantal tekens om door te zoeken (0 schakelt limiet uit). |

### Retourwaarde

Alle gevonden overeenkomsten door herhaaldelijk te matchen.

## Zie ook

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)