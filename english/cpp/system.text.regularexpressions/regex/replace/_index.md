---
title: Replace()
second_title: Aspose.Slides for C++ API Reference
description: Replaces all matches of regex in string with replacement string.
type: docs
weight: 92
url: /cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Replaces all matches of regex in string with replacement string.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| replacement | const [String](../../../system/string/)\& | Replacement string. |

### Return Value

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| replacement | const char_t * | Replacement string. |

### Return Value

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [MatchEvaluator](../../matchevaluator/)\&) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate to generate replacement strings based on matches. |

### Return Value

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [MatchEvaluator](../../matchevaluator/)\&, int) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate to generate replacement strings based on matches. |
| count | int | Number of replacements limit. |

### Return Value

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [MatchEvaluator](../../matchevaluator/)\&, int, int) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate to generate replacement strings based on matches. |
| count | int | Number of replacements limit. |
| startat | int | Index in input string to start replacement at. |

### Return Value

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const char_t *, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const char_t * | [Regex](../) pattern. |
| replacement | const char_t * | Replacement string. |

### Return Value

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pattern. |
| replacement | const char_t * | Replacement string. |

### Return Value

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [MatchEvaluator](../../matchevaluator/)\&, [RegexOptions](../../regexoptions/)) method


Replaces all matches in string with delegate-generated replacement strings (static function).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pattern. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate to generate replacement strings based on matches. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) options. |

### Return Value

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [RegexOptions](../../regexoptions/)) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pattern. |
| replacement | const [String](../../../system/string/)\& | Replacement string. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) options. |

### Return Value

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, int) method


Replaces substrings in string. Not implemented.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, int, int) method


Replaces substrings in string. Not implemented.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Replaces regex matches.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| replacement | const [String](../../../system/string/)\& | Replacement string. |

### Return Value

[String](../../../system/string/) with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
## Regex::Replace(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [MatchEvaluator](../../matchevaluator/)\&) method


Replaces regex matches.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate to generate replacement string for each match. |

### Return Value

[String](../../../system/string/) with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)
