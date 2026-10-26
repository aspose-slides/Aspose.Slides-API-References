---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फ़ाइलों और डायरेक्ट्रीज़ को खोजता है, चाहे वह निर्दिष्ट डायरेक्ट्री में हो या उस डायरेक्ट्री को मूल बनाकर पूरी डायरेक्ट्री ट्री में।
type: docs
weight: 53
url: /hi/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) मेथड


निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फ़ाइलों और डायरेक्ट्रीज़ को खोजता है, चाहे वह निर्दिष्ट डायरेक्ट्री में हो या उस डायरेक्ट्री को मूल बनाकर पूरी डायरेक्ट्री ट्री में।

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | खोज करने वाली डायरेक्ट्री के लिए पूर्ण या रिलेटिव पाथ |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और डायरेक्ट्रीज़ के लिए खोजी जाने वाले नाम का पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्धारित करता है कि खोज केवल निर्दिष्ट डायरेक्ट्री में करनी है या निर्दिष्ट डायरेक्ट्री को मूल बनाकर पूरी डायरेक्ट्री ट्री में करना है |

### रिटर्न वैल्यू

पाई गई फ़ाइलों और डायरेक्ट्रीज़ की पूर्ण पाथ्स का इटेरेबल संग्रह, जिनके नाम **searchPattern** से मिलते हैं।

## संबंधित देखें

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* क्लास [String](../../../system/string/)
* क्लास [Directory](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)