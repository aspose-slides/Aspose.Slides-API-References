---
title: GetNamedItem()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नाम द्वारा निर्दिष्ट XmlNode को प्राप्त करता है।
type: docs
weight: 14
url: /hi/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) विधि

नाम द्वारा निर्दिष्ट एक [XmlNode](../../xmlnode/) को प्राप्त करता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | प्राप्त करने वाले नोड का योग्य नाम। यह मिलते हुए नोड के [XmlNode::get_Name](../../xmlnode/get_name/) मान से मिलान किया जाता है। |

### रिटर्न वैल्यू

निर्दिष्ट नाम वाला एक [XmlNode](../../xmlnode/) या **nullptr** यदि कोई मिलते हुए नोड नहीं मिला।

## XmlNamedNodeMap::GetNamedItem(String, String) विधि

सम्बंधित [XmlNode::get_LocalName](../../xmlnode/get_localname/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) मानों वाले नोड को प्राप्त करता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | प्राप्त करने वाले नोड का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | प्राप्त करने वाले नोड का नामस्थान यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI)। |

### रिटर्न वैल्यू

सम्बंधित स्थानीय नाम और नामस्थान URI वाला एक [XmlNode](../../xmlnode/) या **nullptr** यदि मिलते हुए नोड नहीं मिला।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNamedNodeMap](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)