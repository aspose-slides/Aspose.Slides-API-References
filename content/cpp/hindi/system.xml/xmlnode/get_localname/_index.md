---
title: get_LocalName()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में अधिलेखित किया जाता है, तब नोड का स्थानीय नाम लौटाता है।
type: docs
weight: 209
url: /hi/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() विधि

एक व्युत्पन्न वर्ग में अधिलेखित किए जाने पर नोड का स्थानीय नाम लौटाता है।

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### वापसी मान

उपसर्ग हटाए गए नोड का नाम। उदाहरण के लिए, **LocalName** तत्व **<bk:book>** के लिए **book** है।

## टिप्पणियां

वापस किया गया नाम नोड के [XmlNode::get_NodeType](../get_nodetype/) पर निर्भर करता है:

| प्रकार | नाम |
| --- | --- |
| [Attribute](../../../system/attribute/)| एट्रिब्यूट का स्थानीय नाम। |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | दस्तावेज़ प्रकार का नाम। |
| Element | एलिमेंट का स्थानीय नाम। |
| Entity | इकाई का नाम। |
| EntityReference | संदर्भित इकाई का नाम। |
| Notation | नोटेशन का नाम। |
| ProcessingInstruction | प्रोसेसिंग इंस्ट्रक्शन का लक्ष्य। |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## और देखें

* कक्षा [String](../../../system/string/)
* कक्षा [XmlNode](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)