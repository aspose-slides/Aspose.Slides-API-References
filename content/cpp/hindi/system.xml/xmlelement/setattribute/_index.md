---
title: SetAttribute()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट नाम वाले एट्रिब्यूट का मान सेट करता है।
type: docs
weight: 222
url: /hi/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) मेथड

निर्दिष्ट नाम वाले एट्रिब्यूट का मान सेट करता है।

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | बनाने या बदलने के लिए एट्रिब्यूट का नाम। यह एक योग्य नाम है। यदि नाम में कोलन है तो इसे प्रीफ़िक्स और स्थानीय नाम घटकों में विभाजित किया जाता है। |
| value | [String](../../../system/string/) | एट्रिब्यूट के लिए सेट किया जाने वाला मान। |

## XmlElement::SetAttribute(String, String, String) मेथड

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट का मान सेट करता है।

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |
| value | [String](../../../system/string/) | एट्रिब्यूट के लिए सेट किया जाने वाला मान। |

### वापसी मान

एट्रिब्यूट मान।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlElement](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)