---
title: XmlOutputMethod
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlWriter आउटपुट को सीरियलाइज़ करने के लिए उपयोग की जाने वाली विधि निर्दिष्ट करता है।
type: docs
weight: 846
url: /hi/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

उस विधि को निर्दिष्ट करता है जिसका उपयोग [XmlWriter](../xmlwriter/) आउटपुट को सीरियलाइज़ करने के लिए किया जाता है।

```cpp
enum class XmlOutputMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Xml | 0 | XML 1.0 नियमों के अनुसार सीरियलाइज़ करें। |
| Html | 1 | XSLT द्वारा निर्दिष्ट HTML नियमों के अनुसार सीरियलाइज़ करें। |
| Text | 2 | केवल टेक्स्ट ब्लॉकों को सीरियलाइज़ करें। |
| AutoDetect | 3 | रनटाइम पर [XmlOutputMethod::Xml](./) और [XmlOutputMethod::Html](./) आउटपुट विधियों के बीच चयन करने के लिए XSLT नियमों का उपयोग करें। |

## See Also

* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)