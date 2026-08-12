---
title: GetFiles()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फ़ाइलों की खोज निर्दिष्ट डायरेक्टरी में या निर्दिष्ट डायरेक्टरी से शुरू होने वाले सम्पूर्ण डायरेक्टरी ट्री में की जाती है।
type: docs
weight: 79
url: /hi/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) मेथड

निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फाइलों की खोज निर्दिष्ट डायरेक्टरी में या निर्दिष्ट डायरेक्टरी से शुरू होने वाले सम्पूर्ण डायरेक्टरी ट्री में की जाती है।

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | खोज करने के लिए डायरेक्टरी का पूर्ण या सापेक्ष पथ |
| searchPattern | const [String](../../../system/string/)\& | खोजी जाने वाली फ़ाइलों के नाम का पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | यह निर्दिष्ट करता है कि खोज केवल निर्दिष्ट डायरेक्टरी में की जानी है या निर्दिष्ट डायरेक्टरी के मूल में स्थित पूरी डायरेक्ट्री ट्री में की जानी है |

### रिटर्न मान

एक एरे जिसमें खोजी गई फ़ाइलों के पूर्ण पथ होते हैं, जिनके नाम **searchPattern** से मेल खाते हैं

## संबंधित देखें

* एनम [SearchOption](../../searchoption/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [Directory](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)