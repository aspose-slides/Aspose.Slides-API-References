---
title: get_Name()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तब नोड का योग्य नाम लौटाता है।
type: docs
weight: 1
url: /hi/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() मेथड

जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तब नोड का योग्य नाम लौटाता है।

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### रिटर्न वैल्यू

नोड का योग्य नाम।

## टिप्पणियाँ

वापसी किया गया नाम नोड के [XmlNode::get_NodeType](../get_nodetype/) पर निर्भर करता है:

| प्रकार | नाम |
| --- | --- |
| [Attribute](../../../system/attribute/)| एट्रिब्यूट का योग्य नाम। |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | दस्तावेज़ प्रकार का नाम। |
| Element | एलिमेंट का योग्य नाम। |
| Entity | एंटिटी का नाम। |
| EntityReference | सन्दर्भित एंटिटी का नाम। |
| Notation | नोटेशन नाम। |
| ProcessingInstruction | प्रोसेसिंग इंस्ट्रक्शन का लक्ष्य। |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNode](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)