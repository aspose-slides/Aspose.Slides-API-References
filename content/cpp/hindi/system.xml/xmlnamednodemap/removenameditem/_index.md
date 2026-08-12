---
title: RemoveNamedItem()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XmlNamedNodeMap से नोड को हटाता है।
type: docs
weight: 40
url: /hi/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) मेथड

[XmlNamedNodeMap](../) से नोड को हटाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | हटाने के लिये नोड का योग्य नाम। इस नाम की तुलना मिलते हुए नोड के [XmlNode::get_Name](../../xmlnode/get_name/) मान से की जाती है। |

### रिटर्न मान

इस [XmlNamedNodeMap](../) से हटाया गया [XmlNode](../../xmlnode/) या **nullptr** यदि कोई मेल खाने वाला नोड नहीं मिला।

## XmlNamedNodeMap::RemoveNamedItem(String, String) मेथड

[XmlNode::get_LocalName](../../xmlnode/get_localname/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) मानों से मिलते हुए नोड को हटाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | हटाने के लिये नोड का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | हटाने के लिये नोड का नेमस्पेस URI। |

### रिटर्न मान

हटाया गया [XmlNode](../../xmlnode/) या **nullptr** यदि कोई मेल खाने वाला नोड नहीं मिला।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNamedNodeMap](../)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)