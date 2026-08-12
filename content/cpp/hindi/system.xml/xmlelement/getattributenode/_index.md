---
title: GetAttributeNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम के साथ XmlAttribute लौटाता है।
type: docs
weight: 248
url: /hi/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) मेथड


निर्दिष्ट नाम के साथ [XmlAttribute](../../xmlattribute/) लौटाता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | प्राप्त करने के लिए एट्रिब्यूट का नाम। यह एक क्वालिफ़ाइड नाम है। यह मेल खाने वाले नोड के **get_Name** मान के साथ मिलान किया जाता है। |

### रिटर्न वैल्यू

यदि मेल खाने वाला एट्रिब्यूट नहीं मिला तो निर्दिष्ट [XmlAttribute](../../xmlattribute/) या **nullptr** लौटाता है।

## XmlElement::GetAttributeNode(String, String) मेथड


निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ [XmlAttribute](../../xmlattribute/) लौटाता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

यदि मेल खाने वाला एट्रिब्यूट नहीं मिला तो निर्दिष्ट [XmlAttribute](../../xmlattribute/) या **nullptr** लौटाता है।

## देखें भी

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttribute](../../xmlattribute/)
* क्लास [String](../../../system/string/)
* क्लास [XmlElement](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)