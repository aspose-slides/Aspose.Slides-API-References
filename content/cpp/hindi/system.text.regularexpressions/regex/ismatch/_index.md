---
title: IsMatch()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रेजेक्स को स्ट्रिंग के विरुद्ध मिलाता है।
type: docs
weight: 53
url: /hi/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) विधि

रेजेक्स को स्ट्रिंग के विरुद्ध मिलाता है।

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | लक्षित स्ट्रिंग। |
| startat | int | प्रारम्भिक इंडेक्स। |

### रिटर्न मान

यदि स्ट्रिंग रेजेक्स से मिलती है तो true, अन्यथा false।

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) विधि

जाँचता है कि स्ट्रिंग पैटर्न से मेल खाती है या नहीं।

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)\& | रेजेक्स पैटर्न। |
| options | [RegexOptions](../../regexoptions/) | मैचिंग विकल्प। |
| matchTimeout | [TimeSpan](../../../system/timespan/) | टाइमआउट। |
| startat | int | [Match](../../match/) प्रारम्भिक स्थिति। |

### रिटर्न मान

यदि मिलान पाया जाता है तो true, अन्यथा false।

## देखें भी

* Enum [RegexOptions](../../regexoptions/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)