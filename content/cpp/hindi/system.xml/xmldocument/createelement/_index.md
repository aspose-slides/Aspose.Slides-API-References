---
title: CreateElement()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम के साथ एक तत्व बनाता है।
type: docs
weight: 339
url: /hi/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) विधि

निर्दिष्ट नाम के साथ एक तत्व बनाता है।

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | तत्व का योग्य नाम। यदि नाम में कॉलन है तो [XmlNode::get_Prefix](../../xmlnode/get_prefix/) मान कॉलन से पहले के भाग को दर्शाता है और [XmlDocument::get_LocalName](../get_localname/) मान कॉलन के बाद के भाग को दर्शाता है। योग्य नाम में **xmlns** का प्रीफ़िक्स शामिल नहीं हो सकता। |

### रिटर्न वैल्यू

नया [XmlElement](../../xmlelement/)।

## XmlDocument::CreateElement(const String\&, const String\&) विधि

एक [XmlElement](../../xmlelement/) बनाता है जिसमें योग्य नाम और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) होते हैं।

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | तत्व का योग्य नाम। यदि नाम में कॉलन है तो [XmlNode::get_Prefix](../../xmlnode/get_prefix/) मान कॉलन से पहले के भाग को दर्शाता है और [XmlDocument::get_LocalName](../get_localname/) मान कॉलन के बाद के भाग को दर्शाता है। योग्य नाम में **xmlns** का प्रीफ़िक्स शामिल नहीं हो सकता। |
| namespaceURI | const [String](../../../system/string/)\& | तत्व का नेमस्पेस URI। |

### रिटर्न वैल्यू

नया [XmlElement](../../xmlelement/)।

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) विधि

निर्दिष्ट [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक तत्व बनाता है।

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | नए तत्व का प्रीफ़िक्स (यदि कोई हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समान हैं। |
| localName | const [String](../../../system/string/)\& | नए तत्व का स्थानीय नाम। |
| namespaceURI | const [String](../../../system/string/)\& | नए तत्व का नेमस्पेस URI (यदि कोई हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समान हैं। |

### रिटर्न वैल्यू

नया [XmlElement](../../xmlelement/)।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlElement](../../xmlelement/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)