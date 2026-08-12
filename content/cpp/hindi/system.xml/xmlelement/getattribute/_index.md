---
title: GetAttribute()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है।
type: docs
weight: 209
url: /hi/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) मेथड

निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है।

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | वापस लेने के लिए एट्रिब्यूट का नाम। यह एक क्वालिफाइड नाम है। यह मिलते हुए नोड के **get_Name** मान के साथ मेल खाता है। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रिब्यूट का मान। यदि मिलते हुए एट्रिब्यूट नहीं मिला या एट्रिब्यूट के पास निर्धारित या डिफ़ॉल्ट मान नहीं है तो खाली स्ट्रिंग लौटाई जाएगी।

## XmlElement::GetAttribute(String, String) मेथड

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट का मान लौटाता है।

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | वापस लेने के लिए एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | वापस लेने के लिए एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रिब्यूट का मान। यदि मिलते हुए एट्रिब्यूट नहीं मिला या एट्रिब्यूट के पास निर्धारित या डिफ़ॉल्ट मान नहीं है तो खाली स्ट्रिंग लौटाई जाएगी।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlElement](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)