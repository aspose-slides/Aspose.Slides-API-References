---
title: Matches()
second_title: Aspose.Slides for C++ API hivatkozás
description: Minden egyezést lekér a reguláris kifejezésből a megadott karakterláncban, ismételt kereséssel.
type: docs
weight: 79
url: /hu/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) metódus


Minden egyezést lekér a reguláris kifejezésből a megadott karakterláncban, ismételt egyezéssel.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| startat | int | [Index](../../../system/index/) a kezdő pozíció. |

### Visszatérési érték

Az összes megtalált egyezés gyűjteménye.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metódus


Az összes egyezést lekéri a karakterlánc és a minta között.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Reguláris kifejezés minta. |
| options | [RegexOptions](../../regexoptions/) | Egyezés opciói. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Időkorlát. |
| startat | int | [Match](../../match/) a kezdő pozíció. |
| length | int | Karakterek száma, amelyeken keresni kell (0 letiltja a korlátot). |

### Visszatérési érték

Az összes megtalált egyezés ismételt egyezéssel.

## Lásd még

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)