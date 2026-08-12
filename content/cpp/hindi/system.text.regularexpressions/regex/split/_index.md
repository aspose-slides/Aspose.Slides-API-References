---
title: Split()
second_title: Aspose.Slides for C++ API संदर्भ
description: रेगुलर एक्सप्रेशन मेल द्वारा स्ट्रिंग को विभाजित करता है।
type: docs
weight: 105
url: /hi/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method


रेगुलर एक्सप्रेशन मेल द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### आर्गुमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |

### वापसी मान

[Array](../../../system/array/) of substrings between matches.

## Regex::Split(const String\&, int) method


रेगुलर एक्सप्रेशन मेल द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### आर्गुमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |
| count | int | Number of substrings limit. |

### वापसी मान

[Array](../../../system/array/) of substrings between matches.

## Regex::Split(const String\&, int, int) method


इनपुट स्ट्रिंग को अधिकतम निर्दिष्ट संख्या बार एक नियमित अभिव्यक्ति द्वारा परिभाषित स्थितियों पर सबस्ट्रिंग्स के ऐरे में विभाजित करता है, जो [Regex](../) कन्स्ट्रक्टर में निर्दिष्ट है। नियमित अभिव्यक्ति पैटर्न की खोज इनपुट स्ट्रिंग में एक निर्दिष्ट अक्षर स्थिति से शुरू होती है।

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### आर्गुमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | The string to be split. |
| count | int | The maximum number of times the split can occur. |
| startat | int | The character position in the input string where the search will begin. |

### वापसी मान

स्ट्रिंग्स की एक ऐरे।

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method


रेजेक्स द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### आर्गुमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### वापसी मान

[Array](../../../system/array/) of strings between matchse.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method


रेजेक्स द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### आर्गुमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| count | int | [Match](../../match/) number limit. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### वापसी मान

[Array](../../../system/array/) of strings between matchse.

## संबंधित देखें

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)