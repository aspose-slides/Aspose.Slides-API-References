---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट निर्देशिका में या निर्दिष्ट निर्देशिका से शुरू होने वाले पूरे निर्देशिका वृक्ष में, निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं को खोजता है।
type: docs
weight: 27
url: /hi/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) विधि

निर्दिष्ट निर्देशिका में या निर्दिष्ट निर्देशिका से शुरू होने वाले पूरे निर्देशिका वृक्ष में निर्दिष्ट खोज मानदंडों को पूरा करने वाली निर्देशिकाओं को खोजता है।

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | खोज के लिए निर्देशिका का पूर्ण या सापेक्ष पथ |
| searchPattern | const [String](../../../system/string/)\& | खोजी जाने वाली निर्देशिकाओं के नाम का पैटर्न |
| searchOption | [SearchOption](../../searchoption/) | यह निर्दिष्ट करता है कि खोज केवल निर्दिष्ट निर्देशिका में की जानी है या निर्दिष्ट निर्देशिका से शुरू होने वाले पूरे निर्देशिका वृक्ष में |

### रिटर्न मान

पाए गए निर्देशिकाओं के पूर्ण पथों का आयतनीय संग्रह, जिनके नाम **searchPattern** से मेल खाते हैं

## संबंधित देखें

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)