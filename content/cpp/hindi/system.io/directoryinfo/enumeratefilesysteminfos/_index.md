---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी फ़ाइलों और डायरेक्टरीज़ को शामिल करने वाला एन्यूमेरेबल संग्रह लौटाता है।
type: docs
weight: 131
url: /hi/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी फ़ाइलों और डायरेक्टरीज़ को शामिल करने वाला एन्यूमेरेबल संग्रह लौटाता है।

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंड को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है।

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और डायरेक्टरीज़ को खोजने के लिए नाम पैटर्न |

### रिटर्न वैल्यू

फ़ाइलों और डायरेक्टरीज़ को दर्शाने वाले, जिनके नाम **searchPattern** से मेल खाते हैं, [FileSystemInfo](../../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का एन्यूमेरेबल संग्रह।

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी या उस डायरेक्टरी में मूल स्थापित पूरे डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंड को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है।

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और डायरेक्टरीज़ को खोजने के लिए नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्दिष्ट करता है कि खोज केवल वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में करनी है या उस डायरेक्टरी में मूल स्थापित पूरे डायरेक्टरी ट्री में |

### रिटर्न वैल्यू

फ़ाइलों और डायरेक्टरीज़ को दर्शाने वाले, जिनके नाम **searchPattern** से मेल खाते हैं, [FileSystemInfo](../../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का एन्यूमेरेबल संग्रह।

## देखें

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)