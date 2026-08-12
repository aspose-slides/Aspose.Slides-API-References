---
title: Matches()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दिए गए स्ट्रिंग में regex के सभी मेल प्राप्त करता है, बार-बार मिलान करके।
type: docs
weight: 79
url: /hi/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) विधि

दिए गए स्ट्रिंग में regex के सभी मेल प्राप्त करता है, बार-बार मिलान करके।

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### आर्ग्यूमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | इनपुट स्ट्रिंग। |
| startat | int | [Index](../../../system/index/) मिलान शुरू करने का स्थान। |

### रिटर्न वैल्यू

पाए गए सभी मेलों का संग्रह।

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) विधि

स्ट्रिंग और पैटर्न के बीच के सभी मेल प्राप्त करता है।

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### आर्ग्यूमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | इनपुट स्ट्रिंग। |
| pattern | const [String](../../../system/string/)\& | रेगेक्स पैटर्न। |
| options | [RegexOptions](../../regexoptions/) | मिलान विकल्प। |
| matchTimeout | [TimeSpan](../../../system/timespan/) | समय सीमा। |
| startat | int | [Match](../../match/) प्रारम्भिक स्थिति। |
| length | int | देखे जाने वाले अक्षरों की संख्या (0 सीमा को अक्षम करता है)। |

### रिटर्न वैल्यू

बार-बार मिलान करके पाए गए सभी मेल।

## देखें भी

* एन्यूम [RegexOptions](../../regexoptions/)
* टाइपडेफ़ [MatchCollectionPtr](../../matchcollectionptr/)
* क्लास [String](../../../system/string/)
* क्लास [Regex](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Text::RegularExpressions](../../)
* लाइब्रेरी [Aspose.Slides](../../../)