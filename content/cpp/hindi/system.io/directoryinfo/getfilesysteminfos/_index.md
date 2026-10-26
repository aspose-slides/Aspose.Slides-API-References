---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई निर्देशिका में स्थित सभी फ़ाइलों और निर्देशिकाओं का प्रतिनिधित्व करने वाले FileSystemInfo ऑब्जेक्ट्स के साझा पॉइंटरों को सम्मिलित करने वाला एक एरे लौटाता है।
type: docs
weight: 170
url: /hi/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए निर्देशिका में स्थित सभी फ़ाइलों और निर्देशिकाओं का प्रतिनिधित्व करने वाले [FileSystemInfo](../../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स को सम्मिलित करने वाला एक एरे लौटाता है।

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई निर्देशिका में निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली फ़ाइलों और निर्देशिकाओं की खोज करता है।

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और निर्देशिकाओं के लिए खोजे जाने वाले नाम पैटर्न |

### रिटर्न मान

पाए गए फ़ाइलों और निर्देशिकाओं का प्रतिनिधित्व करने वाले [FileSystemInfo](../../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का एक एरे जिसके नाम **searchPattern** से मेल खाते हैं।

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई निर्देशिका में या उस निर्देशिका से उत्पन्न पूरी निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली फ़ाइलों और निर्देशिकाओं की खोज करता है।

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | फ़ाइलों और निर्देशिकाओं के लिए खोजे जाने वाले नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्दिष्ट करता है कि खोज केवल वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई निर्देशिका में करनी है या उस निर्देशिका से उत्पन्न पूरी निर्देशिका वृक्ष में। |

### रिटर्न मान

पाए गए फ़ाइलों और निर्देशिकाओं का प्रतिनिधित्व करने वाले [FileSystemInfo](../../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटर्स का एक एरे जिसके नाम **searchPattern** से मेल खाते हैं।

## देखें

* एनम [SearchOption](../../searchoption/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* क्लास [DirectoryInfo](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)