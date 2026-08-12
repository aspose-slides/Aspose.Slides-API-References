---
title: CreateNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: "निर्दिष्ट XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name, और XmlNode::get_NamespaceURI के साथ एक XmlNode बनाता है।"
type: docs
weight: 482
url: /hi/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) विधि

निर्दिष्ट XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक [XmlNode](../../xmlnode/) बनाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | नई नोड का XmlNodeType। |
| prefix | const [String](../../../system/string/)\& | नई नोड का प्रीफ़िक्स। |
| name | const [String](../../../system/string/)\& | नई नोड का स्थानीय नाम। |
| namespaceURI | const [String](../../../system/string/)\& | नई नोड का नेमस्पेस URI। |

### रिटर्न वैल्यू

नया [XmlNode](../../xmlnode/)।

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) विधि

निर्दिष्ट नोड प्रकार, [XmlDocument::get_Name](../get_name/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक [XmlNode](../../xmlnode/) बनाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | नई नोड के XmlNodeType का [String](../../../system/string/) संस्करण। यह पैरामीटर नीचे तालिका में सूचीबद्ध मानों में से एक होना चाहिए। |
| name | const [String](../../../system/string/)\& | नई नोड का योग्य नाम। यदि नाम में कोलन शामिल है, तो इसे [XmlNode::get_Prefix](../../xmlnode/get_prefix/) और [XmlDocument::get_LocalName](../get_localname/) घटकों में विभाजित किया जाता है। |
| namespaceURI | const [String](../../../system/string/)\& | नई नोड का नेमस्पेस URI। |

### रिटर्न वैल्यू

नया [XmlNode](../../xmlnode/)।

## टिप्पणियाँ

**nodeTypeString** पैरामीटर केस सेंसिटिव है और नीचे दी गई तालिका में से किसी एक मान होना चाहिए:

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) विधि

निर्दिष्ट XmlNodeType, [XmlDocument::get_Name](../get_name/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक [XmlNode](../../xmlnode/) बनाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | नई नोड का XmlNodeType। |
| name | const [String](../../../system/string/)\& | नई नोड का योग्य नाम। यदि नाम में कोलन शामिल है, तो इसे [XmlNode::get_Prefix](../../xmlnode/get_prefix/) और [XmlDocument::get_LocalName](../get_localname/) घटकों में विभाजित किया जाता है। |
| namespaceURI | const [String](../../../system/string/)\& | नई नोड का नेमस्पेस URI। |

### रिटर्न वैल्यू

नया [XmlNode](../../xmlnode/)।

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)