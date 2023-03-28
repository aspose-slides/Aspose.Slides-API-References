---
title: Split()
second_title: Aspose.Slides for C++ API Reference
description: Splits string by regex matches.
type: docs
weight: 105
url: /cpp/system.text.regularexpressions/regex/split/
---
## Regex::Split(const [String](../../../system/string/)\&) method


Splits string by regex matches.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |

### Return Value

[Array](../../../system/array/) of substrings between matches.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Split(const [String](../../../system/string/)\&, int) method


Splits string by regex matches.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |
| count | int | Number of substrings limit. |

### Return Value

[Array](../../../system/array/) of substrings between matches.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Split(const [String](../../../system/string/)\&, int, int) method


Splits an input string a specified maximum number of times into an array of substrings, at the positions defined by a regular expression specified in the [Regex](../) constructor. The search for the regular expression pattern starts at a specified character position in the input string.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | The string to be split. |
| count | int | The maximum number of times the split can occur. |
| startat | int | The character position in the input string where the search will begin. |

### Return Value

An array of strings.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Split(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [RegexOptions](../../regexoptions/), [TimeSpan](../../../system/timespan/)) method


Splits string by regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Return Value

[Array](../../../system/array/) of strings between matchse.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Split(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, int, [RegexOptions](../../regexoptions/), [TimeSpan](../../../system/timespan/)) method


Splits string by regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| count | int | [Match](../../match/) number limit. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Return Value

[Array](../../../system/array/) of strings between matchse.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
