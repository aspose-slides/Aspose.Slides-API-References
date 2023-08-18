---
title: Match()
second_title: Aspose.Slides for C++ API Reference
description: Matches regex against string.
type: docs
weight: 66
url: /system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Matches regex against string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Target string. |

### Return Value

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, int, int) method


Matches regex against string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Target string. |
| startat | int | Beginning index. |
| length | int | Number of characters to look through (0 to look through the whole string). |

### Return Value

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Matches string and pattern.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) beginning position. |
| length | int | Number of characters to look through (0 diables limit). |

### Return Value

First match found.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)