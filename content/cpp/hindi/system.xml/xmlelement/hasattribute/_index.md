---
title: HasAttribute()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्धारित करता है कि क्या वर्तमान नोड में निर्दिष्ट नाम वाले एट्रिब्यूट मौजूद है।
type: docs
weight: 300
url: /hi/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) विधि


निर्धारित करता है कि क्या वर्तमान नोड में निर्दिष्ट नाम वाला एट्रिब्यूट मौजूद है।

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का नाम खोजने के लिए। यह एक क्वालिफ़ाइड नाम है। यह मिलते नोड के **get_Name** मान के विरुद्ध मिलान किया जाता है। |

### रिटर्न मान

**true** यदि वर्तमान नोड में निर्दिष्ट एट्रिब्यूट है; अन्यथा, **false**।

## XmlElement::HasAttribute(String, String) विधि


निर्धारित करता है कि क्या वर्तमान नोड में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाला एट्रिब्यूट है।

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | खोजने के लिए एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | खोजने के लिए एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न मान

**true** यदि वर्तमान नोड में निर्दिष्ट एट्रिब्यूट है; अन्यथा, **false**।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlElement](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)