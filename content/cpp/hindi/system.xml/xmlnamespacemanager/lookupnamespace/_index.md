---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट प्रीफ़िक्स के लिए नेमस्पेस URI लौटाता है।
type: docs
weight: 118
url: /hi/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) मेथड


Returns the namespace URI for the specified prefix.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | उस प्रीफ़िक्स जिसका namespace URI आप हल करना चाहते हैं। डिफ़ॉल्ट namespace से मेल खाने के लिए, [String::Empty](../../../system/string/empty/) पास करें। |

### वापसी मान

यदि कोई मैप किया गया नेमस्पेस नहीं है तो **prefix** या **nullptr** के लिए namespace URI। लौटाई गई स्ट्रिंग एटमाइज़्ड है। एटमाइज़्ड स्ट्रिंग्स के बारे में अधिक जानकारी के लिए, [XmlNameTable](../../xmlnametable/) क्लास देखें।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNamespaceManager](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)