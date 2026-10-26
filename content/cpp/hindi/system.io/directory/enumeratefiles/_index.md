---
title: EnumerateFiles()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट निर्देशिका में या निर्दिष्ट निर्देशिका की जड़ में स्थित संपूर्ण निर्देशिका वृक्ष में निर्दिष्ट खोज मानदण्ड को पूरा करने वाली फ़ाइलों को खोजता है।
type: docs
weight: 40
url: /hi/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) मेथड

निर्दिष्ट निर्देशिका या निर्दिष्ट निर्देशिका में निहित सम्पूर्ण निर्देशिका वृक्ष में निर्दिष्ट खोज मानदण्ड को पूरा करने वाली फ़ाइलों को खोजता है।

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | खोज करने के लिये निर्देशिका का पूर्ण या सापेक्ष पथ |
| searchPattern | const [String](../../../system/string/)& | खोजी जाने वाली फ़ाइलों का नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्धारित करता है कि खोज केवल निर्दिष्ट निर्देशिका में की जानी चाहिए या सम्पूर्ण निर्देशिका वृक्ष में जो निर्दिष्ट निर्देशिका में निहित है |

### लौटाया गया मान

पाई गई फ़ाइलों के पूर्ण पथों का क्रमबद्ध संग्रह जिनके नाम **searchPattern** से मेल खाते हैं

## संबंधित देखें

* एन्यूम [SearchOption](../../searchoption/)
* टाइपडेफ [StringEnumerablePtr](../stringenumerableptr/)
* क्लास [String](../../../system/string/)
* क्लास [Directory](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)