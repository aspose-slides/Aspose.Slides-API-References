---
title: IsMatch()
second_title: Aspose.Slides for C++ API Reference
description: Matches regex against string.
type: docs
weight: 53
url: /cpp/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method


Matches regex against string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Target string. |
| startat | int | Beginning index. |

### Return Value

True if string matches regex, false otherwise.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method


Checks if string matches pattern.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) beginning position. |

### Return Value

True if match is found, false otherwise.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)