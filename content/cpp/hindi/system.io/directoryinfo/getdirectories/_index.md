---
title: GetDirectories()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए निर्देशिका में स्थित सभी निर्देशिकाओं को दर्शाने वाले DirectoryInfo ऑब्जेक्ट्स के साझा पॉइंटर्स वाली एक एरे लौटाता है।
type: docs
weight: 144
url: /hi/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() मेथड

वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए निर्देशिका में स्थित सभी निर्देशिकाओं को दर्शाते हुए [DirectoryInfo](../) ऑब्जेक्ट्स के साझा पॉइंटर्स की एक एरे लौटाता है।

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) मेथड

वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए निर्देशिका में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजे जाने वाले निर्देशिकाओं के नाम का पैटर्न |

### वापसी मान

एक एरे जिसमें [DirectoryInfo](../) ऑब्जेक्ट्स के साझा पॉइंटर्स होते हैं, जो खोजी गई निर्देशिकाओं को दर्शाते हैं जिनके नाम **searchPattern** से मेल खाते हैं।

## DirectoryInfo::GetDirectories(const String\&, SearchOption) मेथड

वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए निर्देशिका या उस निर्देशिका के मूल में स्थित पूरे निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजे जाने वाले निर्देशिकाओं के नाम का पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | निर्धारित करता है कि खोज केवल वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए निर्देशिका में ही करनी है या उस निर्देशिका के मूल में स्थित पूरे निर्देशिका वृक्ष में करनी है |

### वापसी मान

एक एरे जिसमें [DirectoryInfo](../) ऑब्जेक्ट्स के साझा पॉइंटर्स होते हैं, जो खोजी गई निर्देशिकाओं को दर्शाते हैं जिनके नाम **searchPattern** से मेल खाते हैं।

## देखें भी

* एनम [SearchOption](../../searchoption/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* क्लास [DirectoryInfo](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)