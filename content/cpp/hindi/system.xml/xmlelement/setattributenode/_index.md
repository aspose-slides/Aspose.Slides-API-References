---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XmlAttribute को जोड़ता है।
type: docs
weight: 261
url: /hi/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) विधि

निर्दिष्ट [XmlAttribute](../../xmlattribute/) जोड़ता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | इस तत्व के लिए एट्रीब्यूट संग्रह में जोड़ने हेतु [XmlAttribute](../../xmlattribute/) नोड। |

### Return Value

यदि एट्रीब्यूट उसी नाम के मौजूदा एट्रीब्यूट को बदलता है, तो पुराना [XmlAttribute](../../xmlattribute/) लौटाया जाता है; अन्यथा, **nullptr** लौटाया जाता है।

## XmlElement::SetAttributeNode(String, String) विधि

निर्दिष्ट [XmlAttribute](../../xmlattribute/) जोड़ता है।

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रीब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रीब्यूट का नेमस्पेस URI। |

### Return Value

[XmlAttribute](../../xmlattribute/) जोड़ने के लिए।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttribute](../../xmlattribute/)
* क्लास [XmlElement](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)