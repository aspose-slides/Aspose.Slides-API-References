---
title: Match()
second_title: Aspose.Slides for C++ API संदर्भ
description: रेग्युलर एक्सप्रेशन को स्ट्रिंग के विरुद्ध मिलाता है।
type: docs
weight: 66
url: /hi/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method

रेग्युलर एक्सप्रेशन को स्ट्रिंग के विरुद्ध मिलाता है।

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | लक्ष्य स्ट्रिंग। |

### Return Value

[Match](../../match/) मैच स्थिति और उप-मैचों को सम्मिलित करता हुआ मान।

## Regex::Match(const String\&, int, int) method

रेग्युलर एक्सप्रेशन को स्ट्रिंग के विरुद्ध मिलाता है।

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | लक्ष्य स्ट्रिंग। |
| startat | int | आरम्भिक इंडेक्स। |
| length | int | जाँचने के लिये अक्षरों की संख्या (पूरी स्ट्रिंग को देखने के लिये 0)। |

### Return Value

[Match](../../match/) मैच स्थिति और उप-मैचों को सम्मिलित करता हुआ मान।

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method

स्ट्रिंग और पैटर्न को मिलाता है।

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)\& | रेग्युलर एक्सप्रेशन पैटर्न। |
| options | [RegexOptions](../../regexoptions/) | मैचलिंग विकल्प। |
| matchTimeout | [TimeSpan](../../../system/timespan/) | टाइमआउट। |
| startat | int | [Match](../../match/) आरम्भिक स्थिति। |
| length | int | जाँचने के लिये अक्षरों की संख्या (0 सीमा को अक्षम करता है)। |

### Return Value

पहला मैच मिला।

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)