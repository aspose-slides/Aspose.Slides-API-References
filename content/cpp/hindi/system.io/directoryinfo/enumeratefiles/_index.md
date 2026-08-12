---
title: EnumerateFiles()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए डायरेक्टरी में स्थित सभी फ़ाइलों को शामिल करने वाला क्रमबद्ध संग्रह लौटाता है।
type: docs
weight: 118
url: /hi/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() विधि

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए डायरेक्टरी में स्थित सभी फाइलों को शामिल करने वाले क्रमबद्ध संग्रह को लौटाता है।

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) विधि

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फाइलों को खोजता है।

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों को खोजने के लिए नाम पैटर्न |

### रिटर्न वैल्यू

पाई गई फ़ाइलों का प्रतिनिधित्व करने वाले [FileInfo](../../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का क्रमबद्ध संग्रह, जिनके नाम **searchPattern** से मेल खाते हैं।

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) विधि

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए डायरेक्टरी में या उस डायरेक्टरी से शुरू होने वाले पूरे डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों को खोजता है।

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों को खोजने के लिए नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्दिष्ट करता है कि खोज वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए डायरेक्टरी में ही करनी है या उस डायरेक्टरी से शुरू होने वाले पूरे ट्री में |

### रिटर्न वैल्यू

पाई गई फ़ाइलों का प्रतिनिधित्व करने वाले [FileInfo](../../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का क्रमबद्ध संग्रह, जिनके नाम **searchPattern** से मेल खाते हैं।

## देखें

* एनम [SearchOption](../../searchoption/)
* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ [FileInfoPtr](../../../system/fileinfoptr/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [DirectoryInfo](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)