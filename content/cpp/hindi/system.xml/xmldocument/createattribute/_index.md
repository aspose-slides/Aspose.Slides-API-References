---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम के साथ एक XmlAttribute बनाता है।
type: docs
weight: 274
url: /hi/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) विधि

निर्दिष्ट नाम के साथ एक [XmlAttribute](../../xmlattribute/) बनाता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | विशेषण का योग्य नाम। यदि नाम में कॉलन हो, तो [XmlNode::get_Prefix](../../xmlnode/get_prefix/) मान पहले कॉलन से पहले के भाग को दर्शाता है और [XmlDocument::get_LocalName](../get_localname/) मान पहले कॉलन के बाद के भाग को दर्शाता है। [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) खाली रहता है जब तक प्रीफ़िक्स मान्यता प्राप्त निर्मित प्रीफ़िक्स जैसे **xmlns** न हो। इस मामले में get_NamespaceURI का मान [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) है। |

### रिटर्न वैल्यू

नया [XmlAttribute](../../xmlattribute/)।

## XmlDocument::CreateAttribute(const String\&, const String\&) विधि

निर्दिष्ट योग्य नाम और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक [XmlAttribute](../../xmlattribute/) बनाता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | विशेषण का योग्य नाम। यदि नाम में कॉलन हो तो [XmlNode::get_Prefix](../../xmlnode/get_prefix/) मान कॉलन से पहले के भाग को दर्शाएगा और [XmlDocument::get_LocalName](../get_localname/) मान कॉलन के बाद के भाग को दर्शाएगा। |
| namespaceURI | const [String](../../../system/string/)\& | विशेषण की namespaceURI। यदि योग्य नाम में **xmlns** का प्रीफ़िक्स शामिल हो, तो इस पैरामीटर को [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) होना चाहिए। |

### रिटर्न वैल्यू

नया [XmlAttribute](../../xmlattribute/)।

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) विधि

निर्दिष्ट [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) के साथ एक [XmlAttribute](../../xmlattribute/) बनाता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | विशेषण का प्रीफ़िक्स (यदि हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समतुल्य हैं। |
| localName | const [String](../../../system/string/)\& | विशेषण का स्थानीय नाम। |
| namespaceURI | const [String](../../../system/string/)\& | विशेषण का namespace URI (यदि हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समतुल्य हैं। यदि **prefix** **xmlns** है, तो इस पैरामीटर को [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) होना चाहिए, अन्यथा एक अपवाद फेंका जाएगा। |

### रिटर्न वैल्यू

नया [XmlAttribute](../../xmlattribute/)।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)