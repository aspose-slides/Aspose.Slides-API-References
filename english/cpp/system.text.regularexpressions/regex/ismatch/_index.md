---
title: IsMatch()
second_title: Aspose.Slides for C++ API Reference
description: Matches regex against string.
type: docs
weight: 53
url: /cpp/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const [String](../../../system/string/)\&, int) method


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

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::IsMatch(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [RegexOptions](../../regexoptions/), [TimeSpan](../../../system/timespan/), int) method


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

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
