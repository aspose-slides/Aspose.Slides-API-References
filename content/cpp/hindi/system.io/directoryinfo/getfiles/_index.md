---
title: GetFiles()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी डायरेक्टरी का प्रतिनिधित्व करने वाले FileInfo ऑब्जेक्ट्स के साझा पॉइंटर्स को सम्मिलित करने वाली एरे लौटाता है।
type: docs
weight: 157
url: /hi/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी डायरेक्टरी का प्रतिनिधित्व करने वाले [FileInfo](../../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स को सम्मिलित करने वाली एक एरे लौटाता है।

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फ़ाइलों को खोजता है।

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजी जाने वाली फ़ाइलों के नाम का पैटर्न |

### रिटर्न वैल्यू

एक एरे जिसमें [FileInfo](../../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स होते हैं, जो उन पाए गए फ़ाइलों का प्रतिनिधित्व करते हैं जिनके नाम **searchPattern** से मिलते हैं।

## DirectoryInfo::GetFiles(const String\&, SearchOption) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी या उस डायरेक्टरी को मूल मानते हुए पूरी डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को संतुष्ट करने वाली फ़ाइलों को खोजता है।

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजी जाने वाली फ़ाइलों के नाम का पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | यह निर्धारित करता है कि खोज केवल वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में करनी है या पूरी डायरेक्टरी ट्री में जिसे वह मूल डायरेक्टरी प्रतिनिधित्व करता है |

### रिटर्न वैल्यू

एक एरे जिसमें [FileInfo](../../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स होते हैं, जो उन पाए गए फ़ाइलों का प्रतिनिधित्व करते हैं जिनके नाम **searchPattern** से मिलते हैं।

## संबंधित देखें

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* क्लास [DirectoryInfo](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)