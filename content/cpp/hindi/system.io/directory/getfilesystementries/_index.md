---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: निर्दिष्ट निर्देशिका में या निर्दिष्ट निर्देशिका से शुरू होने वाले पूरे निर्देशिका पेड़ में, निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली फ़ाइलों और निर्देशिकाओं को खोजता है।
type: docs
weight: 92
url: /hi/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) method

फ़ाइलों और डायरेक्टरीज़ को खोजता है जो निर्दिष्ट खोज मानदंड को संतुष्ट करती हैं, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है।

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | खोज करने वाले डायरेक्टरी का पूर्ण या सापेक्ष पाथ |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और डायरेक्टरीज़ के नाम का पैटर्न जिसे खोजा जाना है |
| searchOption | [SearchOption](../../searchoption/) | निर्धारित करता है कि खोज केवल निर्दिष्ट डायरेक्टरी में की जानी है या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है |

### रिटर्न वैल्यू

पाए गए फ़ाइलों और डायरेक्टरीज़ के पूर्ण पाथ का एरे जिनके नाम **searchPattern** से मेल खाते हैं

## संबंधित देखें

* एन्युम [SearchOption](../../searchoption/)
* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [Directory](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)