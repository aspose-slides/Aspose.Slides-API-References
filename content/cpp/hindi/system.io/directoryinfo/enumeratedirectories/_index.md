---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए निर्देशिका में स्थित सभी निर्देशिकाओं को शामिल करने वाला एरेबल संग्रह लौटाता है।
type: docs
weight: 105
url: /hi/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() मेथड


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए निर्देशिका में स्थित सभी निर्देशिकाओं को शामिल करने वाला एरेबल संग्रह लौटाता है।

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) मेथड


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए निर्देशिका में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजे जाने वाले निर्देशिकाओं का नाम पैटर्न |

### रिटर्न वैल्यू

ऐसे खोजे गए निर्देशिकाओं का प्रतिनिधित्व करने वाले [DirectoryInfo](../) ऑब्जेक्ट्स के साझा पॉइंटर्स का एरेबल संग्रह, जिनके नाम **searchPattern** से मेल खाते हैं।

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) मेथड


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए निर्देशिका में या उस निर्देशिका द्वारा मूलित पूरे निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं की खोज करता है।

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | खोजे जाने वाले निर्देशिकाओं का नाम पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | यह निर्दिष्ट करता है कि खोज केवल वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए निर्देशिका में करनी है या पूरे निर्देशिका वृक्ष में |

### रिटर्न वैल्यू

ऐसे खोजे गए निर्देशिकाओं का प्रतिनिधित्व करने वाले [DirectoryInfo](../) ऑब्जेक्ट्स के साझा पॉइंटर्स का एरेबल संग्रह, जिनके नाम **searchPattern** से मेल खाते हैं।

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)