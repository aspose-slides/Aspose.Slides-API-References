---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: "निर्दिष्ट XmlNode::get_Name के साथ पहला चाइल्ड एलिमेंट लौटाता है।"
type: docs
weight: 586
url: /hi/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) मेथड

निर्दिष्ट [XmlNode::get_Name](../get_name/) के साथ पहला चाइल्ड एलिमेंट लौटाता है।

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### आर्ग्यूमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | वह तत्व जिसका पूर्ण नाम पुनः प्राप्त किया जाना है। |

### Return Value

निर्दिष्ट नाम से मेल खाने वाला पहला [XmlElement](../../xmlelement/)। अगर कोई मेल नहीं मिलता तो यह **nullptr** लौटाता है।

## XmlNode::idx_get(String, String) मेथड

निर्दिष्ट [XmlNode::get_LocalName](../get_localname/) और [XmlNode::get_NamespaceURI](../get_namespaceuri/) मानों के साथ पहला चाइल्ड एलिमेंट लौटाता है।

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### आर्ग्यूमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localname | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| ns | [String](../../../system/string/) | तत्व का नामस्थान URI। |

### Return Value

मिलते **localname** और **ns** वाले पहला [XmlElement](../../xmlelement/)। यदि कोई मेल नहीं मिलता तो यह **nullptr** लौटाता है।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlElement](../../xmlelement/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNode](../)
* नामस्थान [System::Xml](../../)
* Library [Aspose.Slides](../../../)