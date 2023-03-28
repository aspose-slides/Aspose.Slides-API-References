---
title: Matches()
second_title: Aspose.Slides for C++ API Reference
description: Gets all matches of regex in given string by matching repeatedly.
type: docs
weight: 79
url: /cpp/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const [String](../../../system/string/)\&, int) method


Gets all matches of regex in given string by matching repeatedly.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| startat | int | Index to start matching at. |

### Return Value

Collection of all matches found.

## See Also

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Matches(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [RegexOptions](../../regexoptions/), [TimeSpan](../../../system/timespan/), int, int) method


Gets all matches between string and pattern.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
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

All matches found by matching repeatedly.

## See Also

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
