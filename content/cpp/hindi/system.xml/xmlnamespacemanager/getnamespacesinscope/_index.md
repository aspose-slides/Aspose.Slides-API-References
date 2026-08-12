---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह प्रीफ़िक्स द्वारा कुंजीबद्ध नेमस्पेस नामों का एक संग्रह लौटाता है, जिसे वर्तमान स्कोप में मौजूद नेमस्पेस को सूचीबद्ध करने के लिए उपयोग किया जा सकता है।
type: docs
weight: 105
url: /hi/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) विधि

यह प्रीफ़िक्स द्वारा कुंजीबद्ध नेमस्पेस नामों का संग्रह लौटाता है, जिसे वर्तमान स्कोप में मौजूद नेमस्पेस को सूचीबद्ध करने के लिये उपयोग किया जा सकता है।

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | एक एन्यूमरेशन मान जो लौटाने के लिए नेमस्पेस नोड के प्रकार को निर्दिष्ट करता है। |

### वापसी मान

वर्तमान स्कोप में मौजूद नेमस्पेस और प्रीफ़िक्स जोड़े का एक संग्रह।

## देखें

* एन्युम [XmlNamespaceScope](../../xmlnamespacescope/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [IDictionary](../../../system.collections.generic/idictionary/)
* वर्ग [String](../../../system/string/)
* वर्ग [XmlNamespaceManager](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)