---
title: GetNamespacesInScope()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान में स्कोप में परिभाषित प्रीफ़िक्स-नेमस्पेस मैपिंग्स का एक संग्रह लौटाता है।
type: docs
weight: 1
url: /hi/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) मेथड


एक संग्रह लौटाता है जिसमें वर्तमान स्कोप में परिभाषित प्रीफ़िक्स-नेमस्पेस मैपिंग्स होते हैं।

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | एक XmlNamespaceScope मान जो लौटाने के लिए नेमस्पेस नोड्स के प्रकार को निर्दिष्ट करता है। |

### रिटर्न वैल्यू

एक IDictionary संग्रह जिसमें वर्तमान इन-स्कोप नेमस्पेस होते हैं।

## देखें भी

* एन्यूम [XmlNamespaceScope](../../xmlnamespacescope/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDictionary](../../../system.collections.generic/idictionary/)
* क्लास [String](../../../system/string/)
* क्लास [IXmlNamespaceResolver](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)