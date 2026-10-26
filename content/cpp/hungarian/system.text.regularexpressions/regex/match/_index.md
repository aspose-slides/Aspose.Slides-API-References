---
title: Match()
second_title: Aspose.Slides C++ API referenciája
description: Reguláris kifejezést illeszt a karakterláncra.
type: docs
weight: 66
url: /hu/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String&) method

Reguláris kifejezést illeszt a karakterláncra.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | Célkarakterlánc. |

### Return Value

[Match](../../match/) érték, amely tartalmazza az egyezés állapotát és az al-egyezéseket.

## Regex::Match(const String&, int, int) method

Reguláris kifejezést illeszt a karakterláncra.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | Célkarakterlánc. |
| startat | int | Kezdőindex. |
| length | int | A keresendő karakterek száma (0 a teljes karakterlánc kereséséhez). |

### Return Value

[Match](../../match/) érték, amely tartalmazza az egyezés állapotát és az al-egyezéseket.

## Regex::Match(const String&, const String&, RegexOptions, TimeSpan, int, int) method

Illeszt egy karakterláncot és egy mintát.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)& | Reguláris kifejezési minta. |
| options | [RegexOptions](../../regexoptions/) | Illesztési beállítások. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Időkorlát. |
| startat | int | [Match](../../match/) kezdőpozíció. |
| length | int | A keresendő karakterek száma (0 a korlát letiltásához). |

### Return Value

Az első egyezés megtalálva.

## Lásd még

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)