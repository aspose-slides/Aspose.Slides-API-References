---
title: GetDirectories()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट निर्देशिका या उस निर्देशिका से शुरू होने वाले पूरी निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।
type: docs
weight: 66
url: /hi/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) विधि

निर्दिष्ट निर्देशिका या निर्दिष्ट निर्देशिका से शुरू होने वाले पूरे निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | सर्च करने वाली निर्देशिका का पूर्ण या सापेक्ष पाथ |
| searchPattern | const [String](../../../system/string/)\& | डायरेक्टरीज़ को खोजने के लिए नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्दिष्ट निर्देशिका में ही खोज करनी है या पूरी निर्देशिका ट्री में, यह निर्धारित करता है |

### रिटर्न वैल्यू

एक एरे जिसमें उन खोजी गई निर्देशिकाओं के पूर्ण पाथ होते हैं जिनके नाम **searchPattern** से मेल खाते हैं

## देखें

* एनम [SearchOption](../../searchoption/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [Directory](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)