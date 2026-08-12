---
title: RemoveAttributeNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XmlAttribute को हटाता है।
type: docs
weight: 274
url: /hi/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) विधि


निर्दिष्ट [XmlAttribute](../../xmlattribute/) को हटाता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | हटाने के लिए [XmlAttribute](../../xmlattribute/) नोड। यदि हटाई गई विशेषता का डिफ़ॉल्ट मान है, तो वह तुरंत प्रतिस्थापित किया जाता है। |

### वापसी मान

हटा दी गई [XmlAttribute](../../xmlattribute/) या **nullptr** यदि **oldAttr** [XmlElement](../) का एट्रिब्यूट नोड नहीं है।

## XmlElement::RemoveAttributeNode(String, String) विधि


स्थानीय नाम और नेमस्पेस URI द्वारा निर्दिष्ट [XmlAttribute](../../xmlattribute/) को हटाता है। (यदि हटाई गई विशेषता का डिफ़ॉल्ट मान है, तो वह तुरंत प्रतिस्थापित किया जाता है)।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### वापसी मान

हटा दी गई [XmlAttribute](../../xmlattribute/) या **nullptr** यदि [XmlElement](../) के पास मिलते-जुलते एट्रिब्यूट नोड नहीं है।

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttribute](../../xmlattribute/)
* क्लास [XmlElement](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)